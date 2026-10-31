# Roblox asset library (from D:\Rodev\template and D:\Rodev\raw-game)

Assets cut out of 38 Roblox places and kits (17 from `D:\Rodev\template`, 13 added 2026-10-30 from
`D:\Rodev\raw-game`, 8 from `Downloads\need_unpack` on 2026-10-31 and 2026-11-01): every UI screen, the whole map, every model, VFX set, material variant,
animation (KeyframeSequence) and sound list, plus measured quality numbers for each game.
Built by `D:\Rodev\tools\rbxdump\extract_library.py`; the skill `roblox-template-library` explains how to
use it while building a game.

- `INDEX.md`: one row per game (genre, source, counts, map size, lighting) and models by tag.
- `QUALITY.md`: benchmarks across games: UI construction, fonts, strokes, corners, palettes, maps,
  lighting and post effects, model sizes.
- `catalog.jsonl`: one JSON object per pack (see fields below). `metrics.json`: every game's raw numbers.

## Per game folder

```
<game>/
  README.md        what is inside, biggest models, UI screens
  reference.md     quality numbers: fonts, colours, strokes, corners, map, lighting, post effects
  metrics.json     the same numbers as JSON
  catalog.jsonl    this game's packs
  ui/_StarterGui-all.rbxm     every StarterGui screen in one insert
  ui/StarterGui/<Screen>.rbxm one screen per file
  ui/<Service>/<path>/<Gui>.rbxm   GUI templates kept in storage (cards, popups, billboards)
  map/workspace.rbxm   the whole Workspace without Terrain and Camera
  map/lighting.rbxm    Sky, Atmosphere, Bloom, ColorCorrection, SunRays, DepthOfField...
  map/environment.json Lighting / Workspace / Terrain properties, post effect values, teams
  models/<Service>/<path>/<Name>.rbxm      one model, tool, accessory or mesh per file
  models/.../<Name>__x<N>.rbxm             N copies of one asset kept with their layout (keycaps, trees, platforms)
  models/.../_vfx.rbxm _parts.rbxm _sounds.rbxm _animations.rbxm   loose items of one folder
  animations/<path>/<Sequence>.rbxm        KeyframeSequences (real animation data)
  animations/animation-ids.json            every Animation instance id with its path
  audio/sounds.json                        every Sound id, volume, looped, speed
  audio/soundservice.rbxm                  SoundService children (groups, ambient sounds)
  map/materials.rbxm   MaterialService children (MaterialVariants, PBR packs); insert into MaterialService
  map/terrain.rbxl     only when the place has terrain: a place with Workspace.Terrain + MaterialService
  models/<Service>/<path>/_other.rbxm      anything no other pack took (plugin saves such as Moon Animator,
                                           chat configs, AvatarSettings, Clouds, values in ServerScriptService)
  coverage.json        instance count check: packed / code only / not packed
```

Games added from `raw-game` (and any game re-extracted later) also go through a completeness pass:
every instance that is not code ends up in some pack, and `coverage.json` lists what was left out. For the
13 raw-game places that is only `Workspace.Camera`, `Workspace.Terrain` (empty in all 13) and
`InsertService.InsertionHash`. A separate check re-read every pack and found every mesh, texture, image,
sound and animation id from each source place inside the packs (10035 ids for "Evade", 15729 for Steal a
Brainrot, and so on). The 17 older games were extracted before this pass and were not re-run.

## Catalog fields

`game, kind (ui | ui-kit | map | lighting | model | model-set | parts | vfx | audio | animations | keyframes |
materials | terrain | other),
file (null when it duplicates another pack), dup_of, source (path in the place), class, instances, parts,
meshparts, unions, emitters, lights, sounds, guis, mesh_ids, image_ids, scripts_removed, scripts_at,
size [x, y, z] studs, tags, kb, set_size, keyframes`

Tags come from folder and model names plus contents: pet, egg, weapon, tool, vehicle, character, vfx,
building, nature, map, sign, accessory, treadmill, keyboard, collectible, cutscene, ability, decoration,
interior, road, portal. UI packs get their own tags: shop, hud, inventory, index, settings, popup, reward, trade,
loading, leaderboard, rebirth, upgrade, quest. Packs from reject, backup, old or test folders are tagged `backup`.

## Importing

- Studio MCP: `import_rbxm` with `source.path` = the absolute file path and `parent_path` = where it goes
  (`StarterGui` for UI, `Workspace` for maps and props, `ReplicatedStorage` / `ServerStorage` for templates,
  `Lighting` for `lighting.rbxm`).
- By hand: right-click the target in the Explorer, Insert from File, pick the `.rbxm`.
- Lighting properties are not inside `lighting.rbxm` (Lighting is a service). Apply them from
  `map/environment.json`; the skill's `scripts/lighting_luau.py` prints the Luau for that.
- All packs were checked: a round trip of 1.6 million property values matched the source, and Studio
  loaded UI kits, a 34,415-model set, a full map and KeyframeSequences with matching counts.

## What does not carry over

- **Scripts are removed** (Script and LocalScript; their children are kept). ModuleScripts stay. Behaviour
  lives in `D:\Rodev\template\_unpacked\<file>\scripts\`; `scripts_at` in the catalog points there.
- **Animation and audio ids belong to the original creators.** Roblox only plays animations owned by the
  game's creator, and private audio does not play elsewhere. Re-upload the KeyframeSequences from
  `animations/` under your own account, and replace sounds.
- **Meshes, images, textures and fonts** are referenced by id and load in Studio, but they still belong to
  their creators.
- Terrain voxels are not exported (Workspace packs have no Terrain).

## Provenance

| Source | Games | How to use |
|---|---|---|
| Template with full source | Drill & Mine, Shrink Keyboard Escape, Bee Swarm Sim remake, Build a Raft, One Piece, Dusty Trip, Trade System, NeeDoh Escape, Animal Hospital, Pass The Bomb | Templates the user has. Building on them is the user's call; check `flags.txt` in `_unpacked` first. |
| Copy of a live game (saveinstance, decompiled) | Steal an Egg, Keyboard Trading, Jujutsu Shenanigans, Bite By Night, Pick a Side, BIG Paintball, Driving Empire | Other studios' work. Study and measure it, then build your own versions. Publishing it as is risks takedown. |
| raw-game, full source | Mine A Brainrot, Punching Simulator, Scooter Obby, Shattered Aether (map), Vergil (character kit), Zombie Outbreak Survival | Same as templates: check `flags.txt` first. |
| raw-game, leak/copy | Doors, Drive For Brainrots, Grow a Garden 2, Murder Mystery 2, Steal a Brainrot, "Evade", Backrooms Exploration | Study and measure only. |

The file `[💎]Evade only for vip new version.rbxl` is not Evade: it is a brainrot steal game (lucky blocks,
brainrot trader, radioactive mutations, fishing). Its folder is still `evade/` so it matches the file name.

Security notes from the scan: the Jujutsu Shenanigans place had a hidden `require(6970565092)` backdoor in two
server Scripts. Both are gone here because scripts are removed, but the original `.rbxl` still has them.
raw-game scan (`D:\Rodev\template\_unpacked\<file>\flags.txt`): "Evade" has 272 HIGH flags, mostly
obfuscated escaped-byte strings and hidden `require()` in server scripts; Steal a Brainrot has Discord
webhooks, code hidden far right of lines and `AdminLoader`/`Fix` scripts hidden inside KeyframeSequences;
Murder Mystery 2 has Discord webhooks and `require()` of asset ids (Adonis plugins). The packs here carry
none of that code, but the source `.rbxl` files do.

## Regenerate

```
python -I D:\Rodev\tools\rbxdump\rbxdump.py D:\Rodev\template --out D:\Rodev\template\_unpacked
python -I D:\Rodev\tools\rbxdump\extract_library.py D:\Rodev\template --out D:\Rodev\asset-library
python -I D:\Rodev\tools\rbxdump\build_docs.py D:\Rodev\asset-library
```

New templates dropped into `D:\Rodev\template` get picked up; add a line to `GAMES` in `extract_library.py`
for a clean folder name and genre.

`extract_library.py` rewrites the top-level `catalog.jsonl` and `metrics.json` with only the files it was
given. When adding games, run it on the new files, then join every game's `catalog.jsonl` and
`metrics.json` into the top-level ones before `build_docs.py`. raw-game files (one is named `.rblx`, which
the folder scan skips, so pass files by name):

```
python -I D:\Rodev\tools\rbxdump\rbxdump.py <files in D:\Rodev\raw-game> --out D:\Rodev\template\_unpacked
python -I D:\Rodev\tools\rbxdump\extract_library.py <files in D:\Rodev\raw-game> --out D:\Rodev\asset-library
```

## Batch 2026-10-31 (from `Downloads\need_unpack`)

Seven files: Tower Of Hell, RIVALS (modded), The Rake (kill test), Work at a Pizza Place, a gore game leak,
and two model packs (100 Weapons Models by mtsowiks: 477 models; Forest Pack by slbr: 56 models).
`extract_library.py` now treats a `.rbxm` with no services as a model pack: every model gets its own file
(no sample + set grouping).

These seven folders also carry the full source, so they do not need `_unpacked`:

```
<game>/source/
  scripts/          every Script / LocalScript / ModuleScript as .luau (same tree as the place)
  scripts.txt       script index     tree.txt   instance tree     ui.txt   every GUI with layout
  remotes.txt       remotes/bindables     assets.txt   asset ids     props.jsonl   full properties
  flags.txt         backdoor / obfuscation scan     README.md   overview
  original/         the untouched source .rbxl / .rbxm (scripts and all)
```

Security notes: The Rake has 50 HIGH flags: free-model virus scripts named `Fix`, `Debounce` and `_` hidden
inside Parts and welds that `require()` Creator Store modules ("antiexploit"/"antibackdoor"), plus an
Adonis admin loader with `loadstring`. Work at a Pizza Place has 3 HIGH flags (HD Admin loader `require` by
id, hidden `require` in `Main` and `GoogleAnalytics`). RIVALS, the gore game, Tower Of Hell and the packs
have none. The `.rbxm` packs carry none of that code; `source/scripts` and `source/original` do.

## Batch 2026-11-01 (from `Downloads\need_unpack`)

Three places. One is a new game, two are other versions of games already here and were merged:

- **Catalogue Avatar Creator** (`catalogue-avatar-creator/`, new): avatar editor / catalog browser, 146 UI
  packs, 41 models, full `source/`.
- **SAE LATEST** = a later build of **Steal an Egg**, merged into `steal-an-egg/`: 681 new packs (49 new
  StarterGui screens), 230 packs that differ from the Beta build kept side by side as `<name>__latest.rbxm`
  (including the SAE map `map/workspace__latest.rbxm`), +108 animation ids, +105 sound ids, and the SAE
  source in `source__latest/`. The Beta build was re-extracted with the current tool, which added 8 packs it
  had missed. Details and the file list: `steal-an-egg/README.md`, `steal-an-egg/merge-report.json`.
- **Grow A Garden 2 -** = the same place as `grow-a-garden-2/` (same assets and scripts, newer save format,
  5 empty services). The packs were kept; its full source was added as `grow-a-garden-2/source/`.

Checks: every non-code instance of all three places is in a pack (`coverage.json`), and every mesh,
texture, image, sound and animation id of each source place (both versions for the merged games) was found
in the packs. The top-level `catalog.jsonl` was rebuilt from the per-game catalogs, which also fixed 47
entries that still pointed at the old paths of the broken Steal an Egg eggs (now in `models/_broken/`).
SAE's 59 HIGH flags are product configs that `require()` a computed path, not backdoors.
