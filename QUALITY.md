# Quality benchmarks

Measured from the 17 places. "Benchmark" rows use the games with at least 500 GUI objects (+1 Drill & Mine, +1 Shrink Keyboard Escape, BIG Paintball! Classic, Bee Swarm Simulator (remake), Bite By Night, Driving Empire, Jujutsu Shenanigans, Pick a Side, Keyboard Trading V2, Steal an Egg, Doors (fully scripted), Drive For Brainrots, Grow a Garden 2 (GAG2), Mine A Brainrot, Murder Mystery 2, Punching Simulator, Scooter Obby, Steal a Brainrot, "Evade" (brainrot game), 100 Weapons Models (mtsowiks), RIVALS (modded), Work at a Pizza Place, Catalogue Avatar Creator). Per-game detail: `<game>/reference.md` and `<game>/metrics.json`.

## 1. UI construction

| Game | ScreenGuis | GUI objects | Scale-only sizes | TextScaled | UIStroke /100 | UIGradient /100 | UICorner /100 | AspectRatio /100 | ImageLabel /100 | Fonts |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|
| +1 Drill & Mine | 4 | 2177 | 99% | 90% | 66.2 | 37.6 | 1.0 | 29.6 | 31.0 | GothamSSm Heavy (551), GothamSSm ExtraBold (494), LegacyArial Regular (106) |
| +1 Shrink Keyboard Escape | 1 | 633 | 98% | 85% | 59.7 | 4.9 | 31.1 | 35.7 | 21.6 | DenkOne Regular (173), DenkOne Bold (49), SourceSansPro Regular (42) |
| BIG Paintball! Classic | 32 | 506 | 69% | 93% | 0.6 | 2.0 | 5.1 | 9.9 | 30.2 | GothamSSm Heavy (106), GothamSSm Bold (39), GothamSSm Medium (12) |
| Bee Swarm Simulator (remake) | 5 | 622 | 79% | 94% | 49.5 | 20.6 | 28.6 | 0.3 | 22.3 | FredokaOne Regular (280), SourceSansPro Regular (18), ComicNeueAngular Regular (12) |
| Bite By Night | 7 | 2509 | 98% | 78% | 8.4 | 33.6 | 1.2 | 9.6 | 53.7 | Inconsolata Light (122), LegacyArial Regular (76), SourceSansPro SemiBold (43) |
| Build a Raft & Sail | 1 | 11 | 36% | 0% | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | - |
| Driving Empire | 7 | 1347 | 91% | 57% | 0.1 | 0.5 | 0.2 | 3.6 | 26.8 | GothamSSm Bold (146), SourceSansPro Regular (111), SourceSansPro SemiBold (75) |
| Jujutsu Shenanigans | 57 | 1366 | 69% | 66% | 7.9 | 3.5 | 5.9 | 10.6 | 43.0 | Finger Paint Regular (212), SourceSansPro Bold (93), SourceSansPro Regular (71) |
| One Piece: The Age Of Pirates | 2 | 10 | 100% | 43% | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | - |
| Pick a Side | 34 | 581 | 27% | 25% | 13.6 | 7.7 | 0.5 | 0.0 | 9.8 | Arial Bold (148), SourceSansPro Regular (74), GothamSSm Heavy (47) |
| +1 NeeDoh Escape | 1 | 241 | 99% | 81% | 46.1 | 7.5 | 9.5 | 64.3 | 31.5 | GothamSSm Heavy (54), SourceSansPro Regular (30), GothamSSm ExtraBold (12) |
| Keyboard Trading V2 | 16 | 3141 | 97% | 77% | 24.4 | 13.1 | 25.6 | 20.9 | 14.1 | Roboto Regular (299), Zekton Regular (272), GothamSSm Bold (197) |
| Steal an Egg | 59 | 3613 | 85% | 69% | 52.5 | 24.7 | 12.6 | 7.1 | 30.6 | GothamSSm Heavy (433), GothamSSm ExtraBold (290), Rubik Bold (156) |
| Animal Hospital | 26 | 353 | 93% | 87% | 23.2 | 9.1 | 4.5 | 15.9 | 33.1 | Silkscreen Regular (20), Noto Serif SC Bold (20), Noto Serif SC Regular (17) |
| Pass The Bomb (Tower) | 3 | 57 | 98% | 73% | 24.6 | 3.5 | 56.1 | 8.8 | 14.0 | Balthazar Regular (11), GothamSSm Bold (7), FredokaOne Regular (7) |
| Doors (fully scripted) | 6 | 1628 | 82% | 92% | 28.3 | 14.9 | 43.9 | 1.8 | 39.2 | LegacyArial Regular (268), Oswald Regular (242), GothamSSm Regular (25) |
| Drive For Brainrots | 2 | 594 | 99% | 87% | 48.3 | 7.1 | 0.2 | 21.4 | 23.6 | GothamSSm Heavy (108), GothamSSm ExtraBold (76), SourceSansPro Regular (31) |
| Grow a Garden 2 (GAG2) | 76 | 4009 | 97% | 97% | 39.7 | 20.7 | 3.3 | 12.9 | 36.0 | ComicNeueAngular Bold (938), SourceSansPro Bold (320), SourceSansPro Regular (259) |
| Mine A Brainrot | 5 | 1052 | 99% | 98% | 46.7 | 16.3 | 3.0 | 12.4 | 25.6 | GothamSSm ExtraBold (225), GothamSSm Bold (163), FredokaOne Regular (21) |
| Murder Mystery 2 | 35 | 18024 | 60% | 53% | 0.2 | 0.7 | 0.2 | 0.5 | 23.5 | SourceSansPro Bold (4912), SourceSansPro Regular (1778), SourceSansPro SemiBold (80) |
| Punching Simulator | 32 | 1649 | 98% | 100% | 47.9 | 11.1 | 14.3 | 9.8 | 23.3 | FredokaOne Regular (385), font asset 12187370000 Bold (201), GothamSSm Heavy (11) |
| Scooter Obby | 15 | 1696 | 98% | 70% | 30.6 | 15.9 | 37.0 | 16.3 | 18.2 | FredokaOne Regular (292), SourceSansPro Regular (134), GothamSSm Bold (22) |
| Steal a Brainrot | 77 | 3653 | 97% | 97% | 47.5 | 8.3 | 1.8 | 5.9 | 21.1 | GothamSSm ExtraBold (695), GothamSSm Bold (265), SourceSansPro Bold (147) |
| Zombie Outbreak Survival | 5 | 66 | 98% | 94% | 19.7 | 7.6 | 25.8 | 7.6 | 9.1 | FredokaOne Regular (9), FredokaOne ExtraBold (8), SourceSansPro Regular (3) |
| "Evade" (brainrot game) | 40 | 2138 | 99% | 100% | 48.7 | 15.4 | 1.1 | 6.0 | 21.6 | GothamSSm ExtraBold (391), SourceSansPro Bold (192), GothamSSm Bold (131) |
| Backrooms Exploration | 5 | 32 | 25% | 0% | 37.5 | 0.0 | 3.1 | 0.0 | 43.8 | LuckiestGuy Regular (7), IndieFlower Regular (3), PressStart2P Regular (3) |
| 100 Weapons Models (mtsowiks) | 8 | 1232 | 5% | 0% | 32.5 | 0.0 | 29.9 | 0.0 | 28.6 | LegacyArial Regular (304), BuilderSans Regular (24), BuilderSans Bold (24) |
| Tower Of Hell | 5 | 256 | 26% | 8% | 0.0 | 0.0 | 0.0 | 5.5 | 31.6 | Zekton Regular (49), SourceSansPro Regular (34), LegacyArial Regular (26) |
| RIVALS (modded) | 11 | 1269 | 92% | 95% | 6.0 | 12.7 | 3.2 | 1.5 | 36.1 | Rubik Bold (53), Rubik Heavy (41), Rubik Medium (35) |
| The Rake (kill test) | 19 | 70 | 91% | 95% | 0.0 | 0.0 | 0.0 | 50.0 | 10.0 | - |
| Work at a Pizza Place | 2 | 1242 | 41% | 22% | 0.0 | 0.0 | 0.0 | 5.6 | 16.7 | LegacyArial Regular (248), SourceSansPro Regular (217), SourceSansPro Bold (63) |
| Catalogue Avatar Creator | 35 | 2489 | 92% | 60% | 12.1 | 1.7 | 25.2 | 12.5 | 14.1 | SourceSansPro Regular (336), Builder Sans SemiBold (212), Builder Sans Regular (158) |

**Benchmark (commercial UIs):**

- Scale-only sizes: 4.55 - 99.16 (median 92.49) %
- TextScaled share: 0.0 - 1.0 (median 0.85)
- UIStroke per 100 GUI objects: 0.0 - 66.2 (median 30.6)
- UIGradient per 100: 0.0 - 37.6 (median 11.1)
- UICorner per 100: 0.0 - 43.9 (median 3.3)
- UIAspectRatioConstraint per 100: 0.0 - 35.7 (median 9.6)
- ImageLabel per 100: 9.8 - 53.7 (median 23.6) (art-heavy UIs are image-built, not flat frames)
- Unique UI images per game: 32 - 393 (median 107)

## 2. Fonts

| Font (family + weight) | Uses | Games |
|---|---:|---:|
| SourceSansPro Bold | 5836 | 13 |
| SourceSansPro Regular | 3295 | 23 |
| GothamSSm ExtraBold | 2186 | 8 |
| GothamSSm Heavy | 1708 | 13 |
| FredokaOne Regular | 1316 | 16 |
| LegacyArial Regular | 1135 | 14 |
| GothamSSm Bold | 1094 | 16 |
| ComicNeueAngular Bold | 955 | 3 |
| Zekton Regular | 329 | 4 |
| Roboto Regular | 301 | 2 |
| SourceSansPro SemiBold | 251 | 5 |
| Oswald Regular | 242 | 1 |
| Arial Bold | 218 | 4 |
| Finger Paint Regular | 212 | 1 |
| Builder Sans SemiBold | 212 | 1 |
| Rubik Bold | 209 | 2 |
| font asset 12187370000 Bold | 201 | 1 |
| DenkOne Regular | 173 | 1 |
| Builder Sans Regular | 158 | 1 |
| Builder Sans Medium | 132 | 1 |
| ComicNeueAngular Regular | 122 | 4 |
| Inconsolata Light | 122 | 1 |
| Roboto Light | 118 | 1 |
| Builder Sans Bold | 101 | 1 |
| GothamSSm Regular | 91 | 6 |

## 3. Strokes and corners

Stroke thickness (`px` = FixedSize, `scaled` = StrokeSizingMode ScaledSize, a fraction of the element):

`3.0 px` ×3205, `2.0 px` ×1818, `0.05 scaled` ×1119, `4.0 px` ×911, `0.06 scaled` ×423, `5.0 px` ×374, `1.5 px` ×335, `0.07 scaled` ×309, `0.04 scaled` ×285, `1.0 px` ×261, `0.02 scaled` ×227, `0.1 scaled` ×211, `0.03 scaled` ×172, `0.01 scaled` ×170

Corner radius (`{scale,offset}`; `{1,0}` = pill/circle):

`{1.0,0}` ×1021, `{0.0,8}` ×877, `{0.2,0}` ×340, `{0.1,0}` ×322, `{0.0,4}` ×293, `{0.05,0}` ×154, `{0.3,0}` ×143, `{0.15,0}` ×132, `{0.5,0}` ×123, `{0.0,2}` ×107, `{0.25,0}` ×105, `{0.0,6}` ×102, `{0.0,3}` ×87, `{0.02,0}` ×65

## 4. Palettes

| Game | Panel colours | Text colours | Stroke colours |
|---|---|---|---|
| +1 Drill & Mine | `#ffffff` `#000000` `#161616` `#191919` `#121212` `#0f1133` `#141414` | `#ffffff` `#000000` `#1b2a35` `#ddffb8` | `#000000` `#4b4b4b` `#323232` `#ffffff` |
| +1 Shrink Keyboard Escape | `#ffc906` `#ffffff` `#ac7c42` `#000000` `#2f2f2f` `#3f3f3f` `#ff6658` | `#ffffff` `#000000` `#989898` `#1ce711` | `#000000` `#462813` `#a70000` `#59ff00` |
| BIG Paintball! Classic | `#000000` `#ffffff` `#00ff00` `#e7e7e7` `#fd9e42` `#3eff8b` `#545454` | `#000000` `#ffffff` `#8c8c8c` `#ffdf3e` | `#72088c` `#ffd21d` `#000000` |
| Bee Swarm Simulator (remake) | `#ffffff` `#000000` `#1e1e1e` `#2f2f2f` `#e25252` `#5ae258` `#ff3c3c` | `#ffffff` `#393939` `#000000` `#141414` | `#1e1e1e` `#141414` `#424242` `#000000` |
| Bite By Night | `#000000` `#ffffff` `#7f0000` `#5d0000` `#020000` `#390000` `#9d0000` | `#ffffff` `#1b2a35` `#d3d1ce` `#000000` | `#ffffff` `#000000` `#c70000` `#840000` |
| Build a Raft & Sail | `#000000` `#003366` `#3333ff` `#000066` `#ff0000` | `#ffffff` `#1b2a35` | - |
| Driving Empire | `#aa0000` `#aaaaaa` `#969796` `#2a2a2a` `#ffffff` `#000000` `#303030` | `#ffffff` `#ffaa00` `#d1d1d1` `#00bf00` | `#323232` |
| Jujutsu Shenanigans | `#ffffff` `#000000` `#a3a2a5` `#55ff00` `#1f1f1f` `#55ffff` `#ffaaff` | `#000000` `#ffffff` `#ff0000` `#464646` | `#000000` `#ffffff` `#55ffff` |
| One Piece: The Age Of Pirates | `#b69163` `#cba26f` `#336d2f` `#4ea849` | `#ffcd7c` `#1b2a35` `#191919` | - |
| Pick a Side | `#000000` `#ffffff` `#ffec1a` `#ff0000` `#8c6e02` `#005012` `#505050` | `#ffffff` `#000000` `#1b2a35` `#00ff00` | `#000000` `#616161` |
| +1 NeeDoh Escape | `#ffffff` `#000000` | `#ffffff` `#000000` `#e62e49` `#ff5555` | `#000000` `#ffffff` `#640000` `#323232` |
| Keyboard Trading V2 | `#000000` `#ffffff` `#5e56d5` `#1c1f25` `#4b4b4b` `#dddddd` `#1d2e4d` | `#ffffff` `#000000` `#c8c8c8` `#dcdcdc` | `#000000` `#ffffff` `#540000` `#00163a` |
| Steal an Egg | `#ffffff` `#000000` `#ff1414` `#444456` `#70ff18` `#e8ebed` `#323241` | `#ffffff` `#191b1d` `#1b2a35` `#51575e` | `#000000` `#151515` `#0b4800` `#beffb4` |
| Animal Hospital | `#000000` `#ffffff` `#787a81` `#db4aff` `#121212` `#1c1c28` `#ffe228` | `#ffffff` `#000000` `#ff2600` `#b2b1b3` | `#000000` `#ffffff` `#000a01` `#00f900` |
| Pass The Bomb (Tower) | `#212121` `#282828` `#464646` `#ffffff` `#1e1e1e` `#2a2a2a` `#000000` | `#ffffff` `#000000` `#b7b7b7` `#feffff` | `#ffffff` `#000000` `#a3a3a3` `#797979` |
| Doors (fully scripted) | `#261919` `#ffdebd` `#665247` `#2a0c07` `#013b06` `#5e2a2b` `#ffffff` | `#ffdebd` `#ffffff` `#d2ffb9` `#ffc9b3` | `#ffdebd` `#ff4b2b` `#d2ffb9` `#ffabab` |
| Drive For Brainrots | `#000000` `#ffffff` `#2b2b2b` `#111111` `#78ff3e` `#070707` `#ff4141` | `#ffffff` `#000000` `#ff0059` `#2bd1ff` | `#000000` `#838383` `#194b00` `#1b0001` |
| Grow a Garden 2 (GAG2) | `#000000` `#eee4da` `#ffffff` `#9c9c9c` `#27140b` `#a3a2a5` `#00aaff` | `#ffffff` `#000000` `#143000` `#1b2a35` | `#000000` `#281b00` `#143000` `#3f0000` |
| Mine A Brainrot | `#ffffff` `#282828` `#000000` `#1e1e1e` `#72ff59` `#515151` `#232543` | `#ffffff` `#000000` `#ffbf50` `#40dcff` | `#000000` `#550324` `#5b0000` `#1a1a1a` |
| Murder Mystery 2 | `#ffffff` `#000000` `#393939` `#00d5ff` `#111111` `#1e1e1e` `#212121` | `#ffffff` `#1b2a35` `#d5d5d5` `#ff0000` | `#ffffff` `#000000` `#ad9f77` `#363636` |
| Punching Simulator | `#ffffff` `#000000` `#002fb6` `#0e286d` `#0050ff` `#009bff` `#fff0ff` | `#ffffff` `#000000` `#3bfc00` `#e8fffd` | `#000000` `#131313` `#17171d` `#045400` |
| Scooter Obby | `#ffffff` `#36af23` `#4fff34` `#000000` `#9d9d00` `#ffff00` `#ff3333` | `#ffffff` `#000000` `#ffda0b` `#9d00ff` | `#000000` `#36af23` `#ffffff` `#00aaff` |
| Steal a Brainrot | `#000000` `#ffffff` `#519e56` `#fdcb35` `#5eb1ff` `#7f7f7f` `#ffff00` | `#ffffff` `#000000` `#ff1919` `#d6d6d6` | `#000000` `#ffffff` `#101d11` `#05102b` |
| Zombie Outbreak Survival | `#000000` `#222b22` `#dddddd` `#181818` `#141514` `#d8d8d8` | `#ffffff` `#212121` `#000000` `#ffc800` | `#000000` `#ffffff` |
| "Evade" (brainrot game) | `#000000` `#519e56` `#ffffff` `#ffff00` `#363230` `#55707f` `#f0c630` | `#ffffff` `#9c9c9c` `#caffc9` `#000000` | `#000000` `#ffffff` `#101d11` `#ffe0e0` |
| Backrooms Exploration | `#ffffff` `#fcff37` | `#f9d11b` `#000000` `#ffffff` | `#602401` `#000000` |
| 100 Weapons Models (mtsowiks) | `#191a1f` `#ff5f57` `#335fff` `#f2f2f4` `#2e3038` `#13235d` `#2f3039` | `#1b2a35` `#000000` `#bcbec8` `#f0f0f3` | `#000000` `#2e3038` `#9c9ea6` `#335fff` |
| Tower Of Hell | `#f0f0f0` `#9e9e9e` `#ffffff` `#303030` `#a3a2a5` `#ffaa7f` | `#ffffff` `#1b2a35` `#00ff00` `#646464` | - |
| RIVALS (modded) | `#00ff00` `#ff00ff` `#0000ff` `#ababab` `#000000` `#ab8a48` `#ffffff` | `#ffffff` `#000000` `#1bd09d` `#728cff` | `#000000` `#062d21` `#ffffff` `#1f1f1f` |
| The Rake (kill test) | `#000000` `#323232` `#959595` `#313135` `#444444` `#242427` | `#ffffff` `#00ff00` `#ff0000` `#000000` | - |
| Work at a Pizza Place | `#1b2a35` `#ffffff` `#1f1f1f` `#a3a2a5` `#000000` `#0d69ac` `#111111` | `#ffffff` `#1b2a35` `#000000` `#f7e559` | - |
| Catalogue Avatar Creator | `#212227` `#2b2d33` `#ffffff` `#121215` `#fdfdff` `#6f7075` `#000000` | `#000000` `#ffffff` `#f7f7f8` `#edeeee` | `#46444d` `#f7f5ff` `#ffffff` `#212227` |

## 5. Maps and builds

| Game | Parts | MeshPart share | Unions | Lights | Emitters | Beams+Trails | World GUIs | Prompts | Core size (studs) | Top materials |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---|---|
| +1 Drill & Mine | 7472 | 2% | 14 | 466 | 817 | 124 | 249 | 5 | 2900x1288x422 | Plastic (6385), Neon (483), SmoothPlastic (461) |
| +1 Shrink Keyboard Escape | 3969 | 18% | 3 | 0 | 312 | 24 | 351 | 4 | 8190x36x1651 | Plastic (3666), Fabric (234), Neon (48) |
| BIG Paintball! Classic | 1957 | 0% | 0 | 8 | 4 | 0 | 0 | 0 | 386x253x378 | SmoothPlastic (1917), Plastic (38), ForceField (2) |
| Bee Swarm Simulator (remake) | 7285 | 90% | 74 | 68 | 36 | 2 | 137 | 0 | 7277x2036x4758 | SmoothPlastic (3780), Plastic (3094), Neon (277) |
| Bite By Night | 865 | 71% | 6 | 42 | 5 | 4 | 8 | 20 | 71x38x777 | Plastic (570), Neon (193), Basalt (60) |
| Build a Raft & Sail | 668 | 0% | 0 | 0 | 0 | 0 | 0 | 0 | 8004x655x2878 | Plastic (312), Slate (208), Ice (92) |
| Driving Empire | 21814 | 13% | 400 | 665 | 137 | 43 | 153 | 0 | 3242x167x4444 | Concrete (5958), SmoothPlastic (5787), Metal (3013) |
| Jujutsu Shenanigans | 10509 | 1% | 3 | 272 | 1 | 1 | 12 | 44 | 556x174x698 | Plastic (6365), Metal (1392), Concrete (773) |
| One Piece: The Age Of Pirates | 2429 | 0% | 0 | 0 | 0 | 0 | 0 | 0 | 2604x1153x2472 | Plastic (962), Wood (627), Brick (361) |
| Pick a Side | 371 | 2% | 4 | 23 | 32 | 12 | 24 | 2 | 165x72x167 | Metal (120), Plastic (103), SmoothPlastic (47) |
| The Dusty Trip (framework) | 15 | 0% | 1 | 1 | 0 | 0 | 0 | 0 | - | Wood (6), Plastic (6), Metal (2) |
| +1 NeeDoh Escape | 36075 | 69% | 8 | 2 | 40 | 24 | 76 | 3 | 5367x115x852 | Glass (14672), Plastic (10773), SmoothPlastic (10423) |
| Keyboard Trading V2 | 40355 | 94% | 308 | 13 | 48 | 44 | 68 | 6 | 4848x490x153 | SmoothPlastic (34430), Plastic (5894), Sand (16) |
| Steal an Egg | 19277 | 8% | 1 | 10 | 410 | 226 | 83 | 65 | 9633x17223x16155 | Wood (12360), Plastic (6219), Neon (369) |
| Animal Hospital | 3765 | 7% | 34 | 56 | 17 | 3 | 219 | 120 | 184x18x229 | SmoothPlastic (1448), Plastic (845), Metal (498) |
| Pass The Bomb (Tower) | 1076 | 10% | 13 | 36 | 1 | 0 | 4 | 0 | 240x161x240 | Marble (403), Glass (245), Neon (240) |
| Doors (fully scripted) | 980 | 47% | 3 | 59 | 28 | 4 | 26 | 14 | 517x930x384 | Wood (422), Metal (182), Concrete (65) |
| Drive For Brainrots | 2227 | 0% | 12 | 0 | 3 | 1 | 10 | 1 | 308x49x1785 | Plastic (2219), Neon (6), SmoothPlastic (2) |
| Grow a Garden 2 (GAG2) | 2863 | 1% | 0 | 0 | 26 | 4 | 38 | 42 | 1091x180x371 | Plastic (2311), Neon (344), Glacier (202) |
| Mine A Brainrot | 5360 | 5% | 391 | 0 | 51 | 2 | 213 | 6 | 594x228x424 | Plastic (5351), Neon (4), SmoothPlastic (3) |
| Murder Mystery 2 | 3350 | 35% | 31 | 12 | 39 | 3 | 58 | 1 | 310x278x142 | WoodPlanks (764), Sand (658), Wood (632) |
| Punching Simulator | 2489 | 55% | 33 | 106 | 298 | 44 | 56 | 0 | 1353x3913x11862 | Plastic (1528), SmoothPlastic (553), Neon (323) |
| Scooter Obby | 1309 | 6% | 28 | 4 | 420 | 3 | 4489 | 0 | 1291x229x20510 | SmoothPlastic (872), Plastic (313), Neon (53) |
| Shattered Aether (map) | 4283 | 94% | 1 | 0 | 26 | 0 | 0 | 0 | 811x162x551 | Plastic (1311), Rock (1064), Limestone (955) |
| Steal a Brainrot | 4625 | 23% | 44 | 3 | 1142 | 110 | 88 | 30 | 491x13545x1281 | Plastic (2869), SmoothPlastic (1283), Glacier (237) |
| Vergil (character kit) | 34 | 15% | 0 | 0 | 102 | 0 | 0 | 0 | 21x13x8 | Plastic (26), Glass (4), Neon (2) |
| Zombie Outbreak Survival | 1014 | 12% | 104 | 8 | 8 | 0 | 24 | 0 | 248x38x138 | Plastic (780), WoodPlanks (168), Metal (28) |
| "Evade" (brainrot game) | 3324 | 24% | 0 | 34 | 903 | 76 | 162 | 183 | 495x135256x475 | Plastic (1888), SmoothPlastic (1000), Neon (433) |
| Backrooms Exploration | 113 | 1% | 16 | 16 | 0 | 0 | 9 | 0 | 45x10x43 | Metal (46), SmoothPlastic (30), Neon (18) |
| Tower Of Hell | 206 | 0% | 8 | 0 | 3 | 0 | 0 | 0 | 112x309x161 | Plastic (191), SmoothPlastic (12), Neon (3) |
| RIVALS (modded) | 5020 | 49% | 11 | 103 | 346 | 88 | 338 | 30 | 7048x4734x1131 | Plastic (1285), SmoothPlastic (1017), Metal (807) |
| The Rake (kill test) | 2809 | 7% | 238 | 20 | 20 | 0 | 1 | 5 | 418x66x371 | CorrodedMetal (1071), SmoothPlastic (562), Plastic (315) |
| Work at a Pizza Place | 4903 | 0% | 25 | 36 | 2 | 0 | 106 | 0 | 1707x72x1014 | Brick (1593), Wood (1019), CorrodedMetal (542) |
| Gore game (leak) | 941 | 16% | 2 | 0 | 0 | 126 | 1 | 0 | 360x99x167 | SmoothPlastic (570), Plastic (241), Concrete (77) |
| Catalogue Avatar Creator | 5 | 20% | 0 | 0 | 0 | 0 | 0 | 0 | - | Plastic (5) |

## 6. Lighting and post-processing

| Game | Technology | Brightness | Time | Ambient | Outdoor | EnvDiffuse | EnvSpecular | Exposure | Shadow softness | Post effects (enabled values) |
|---|---|---:|---|---|---|---:|---:|---:|---:|---|
| +1 Drill & Mine | ShadowMap | 1.5 | 12:00:00 | `#fffcf5` | `#6f6f6f` | 0.75 | 0.0 | 0.0 | 0.2 | ColorCorrection Brig=0.0 Cont=0.25 Satu=0.1 Tint=#ffffff; Bloom Inte=0.1 Size=0.0 Thre=0.0 |
| +1 Shrink Keyboard Escape | ShadowMap | 3.0 | 14:00:00 | `#787878` | `#a5a5a5` | 1.0 | 1.0 | 0.1 | 0.2 | ColorCorrection Brig=0.05 Cont=0.0 Satu=0.0 Tint=#fffaf5; SunRays Inte=0.08 Spre=0.9; Blur Size=0.0; Atmosphere Dens=0.22 Haze=0.0 Glar=0.0 |
| BIG Paintball! Classic | Voxel | 2.5 | 10:54:00 | `#b682ea` | `#7bc9e1` | 0.0 | 0.0 | 0.0 | 0.5 | Atmosphere Dens=0.214 Haze=1.22 Glar=1.34; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.65 Tint=#ffffff; DepthOfField FarI=0.267; Blur Size=8.0 |
| Bee Swarm Simulator (remake) | Voxel | 3.0 | 14:00:00 | `#0c3282` | `#0c3282` | 0.5 | 0.5 | 0.0 | 0.2 | Bloom Inte=0.15 Size=56.0 Thre=0.95; ColorCorrection Brig=0.08 Cont=0.02 Satu=0.4 Tint=#ffffff; SunRays Inte=0.25 Spre=1.0 |
| Bite By Night | Future | 0.0 | 10:00:00 | `#000000` | `#1b4050` | 1.0 | 0.815 | 0.0 | 0.0 | - |
| Build a Raft & Sail | - | 1.0 | 14:00:00 | `#ffffff` | `#808080` | - | - | - | - | - |
| Driving Empire | Compatibility | 2.7 | 13:15:52 | `#000000` | `#6c6c6b` | 1.0 | 0.5 | 0.45 | 0.05 | ColorCorrection Brig=0.009 Cont=0.1 Satu=0.05 Tint=#ffffff; Bloom Inte=1.0 Size=44444.0 Thre=3.67; SunRays Inte=0.017 Spre=0.19; Atmosphere Dens=0.122 Haze=2.07 Glar=0.0 |
| Jujutsu Shenanigans | ShadowMap | 1.0 | 14:30:00 | `#ffffff` | `#ffffff` | 1.0 | 1.0 | 0.0 | 0.2 | - |
| One Piece: The Age Of Pirates | - | 0.2 | 10:00:00 | `#808080` | `#808080` | - | - | - | - | - |
| Pick a Side | Voxel | 1.0 | 14:00:00 | `#7f7f7f` | `#7f7f7f` | 0.0 | 0.0 | 0.0 | 0.5 | - |
| The Dusty Trip (framework) | ShadowMap | 3.0 | 14:30:00 | `#464646` | `#464646` | 1.0 | 1.0 | 0.0 | 0.2 | SunRays Inte=0.01 Spre=0.1; Atmosphere Dens=0.3 Haze=0.0 Glar=0.0; Bloom Inte=1.0 Size=24.0 Thre=2.0 |
| Keyboard Trading V2 | ShadowMap | 2.06 | 14:00:00 | `#7d7d7d` | `#464646` | 1.0 | 1.0 | 0.0 | 0.2 | SunRays Inte=0.01 Spre=0.1; Bloom Inte=0.5 Size=24.0 Thre=2.0; Atmosphere Dens=0.252 Haze=0.0 Glar=0.0; Blur Size=0.0 |
| Steal an Egg | ShadowMap | 2.5 | 11:36:00 | `#dac79c` | `#92c9e2` | 0.75 | 0.7 | 0.0 | 0.2 | SunRays Inte=0.01 Spre=0.5 |
| Animal Hospital | ShadowMap | 0.0 | 20:00:00 | `#91979d` | `#000000` | 0.25 | 0.25 | 0.0 | 0.2 | Atmosphere Dens=0.4 Haze=0.01 Glar=10.0; Bloom Inte=1.0 Size=24.0 Thre=2.0; Blur Size=1.0; ColorCorrection Brig=0.0 Cont=0.3 Satu=1.0 Tint=#f3f2ff; DepthOfField FarI=0.025 |
| Pass The Bomb (Tower) | Voxel | 1.9812 | 13:00:00 | `#242424` | `#c7c7c7` | 0.0 | 0.0 | 0.0 | 0.5 | Blur Size=4.5; ColorCorrection Brig=0.1 Cont=0.3 Satu=0.1 Tint=#97b6ff; SunRays Inte=0.25 Spre=1.0; Bloom Inte=0.0 Size=24.0 Thre=0.95 |
| Doors (fully scripted) | Future | 0.0 | 11:00:00 | `#000000` | `#000000` | 0.0 | 0.0 | 0.4 | 0.61 | - |
| Drive For Brainrots | ShadowMap | 1.6 | 11:18:00 | `#aacfff` | `#d8d3e2` | 0.1 | 0.4 | 0.0 | 0.2 | Bloom Inte=0.5 Size=50.0 Thre=2.0; ColorCorrection Brig=0.3 Cont=0.3 Satu=0.2 Tint=#b8beed; DepthOfField FarI=0.0; SunRays Inte=0.01 Spre=1.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Atmosphere Dens=0.0 Haze=0.35 Glar=1.3 |
| Grow a Garden 2 (GAG2) | ShadowMap | 2.0 | 08:04:19 | `#8a8a8a` | `#808080` | 0.0 | 0.0 | 0.0 | 0.2 | DepthOfField FarI=0.75; Blur Size=0.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff |
| Mine A Brainrot | ShadowMap | 1.3 | 12:00:00 | `#d5e6ff` | `#f6d0ff` | 0.33 | 0.25 | 0.1 | 0.2 | ColorCorrection Brig=0.08 Cont=0.2 Satu=0.7 Tint=#ffffff |
| Murder Mystery 2 | Compatibility | 2.0 | 12:00:00 | `#9d9d9d` | `#9d9d9d` | 0.0 | 0.0 | 0.0 | 0.5 | - |
| Punching Simulator | Voxel | 1.0 | 11:31:19 | `#ffa8a5` | `#c6b8ff` | 0.25 | 0.25 | 0.0 | 0.5 | ColorCorrection Brig=0.1 Cont=0.15 Satu=0.15 Tint=#ffffff; Blur Size=0.0 |
| Scooter Obby | Voxel | 1.5 | 14:47:20 | `#b883ec` | `#dadada` | 0.2 | 0.5 | 0.0 | 0.2 | Bloom Inte=3.0 Size=24.0 Thre=2.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Bloom Inte=0.0 Size=0.0 Thre=5.0; Atmosphere Dens=0.34 Haze=0.0 Glar=0.0; ColorCorrection Brig=0.2 Cont=0.3 Satu=0.3 Tint=#ffffff; SunRays Inte=0.013 Spre=0.352 |
| Shattered Aether (map) | Future | 5.0 | 15:00:00 | `#98b6b0` | `#c6e6cc` | 0.631 | 0.0 | 0.14 | 0.05 | SunRays Inte=0.051 Spre=0.308; Atmosphere Dens=0.43 Haze=2.03 Glar=0.5; Bloom Inte=1.0 Size=24.0 Thre=2.0; ColorCorrection Brig=0.0 Cont=0.3 Satu=0.1 Tint=#e2faff |
| Steal a Brainrot | ShadowMap | 0.5 | 14:00:00 | `#f1f1f1` | `#d4d4d4` | 1.0 | 0.5 | 0.0 | 0.2 | ColorCorrection Brig=0.1 Cont=0.1 Satu=0.4 Tint=#ffe9e9; SunRays Inte=0.0 Spre=1.0 |
| Vergil (character kit) | ShadowMap | 0.89 | 17:06:00 | `#505050` | `#464646` | 1.0 | 1.0 | -0.75 | 0.0 | SunRays Inte=0.135 Spre=0.115; Bloom Inte=1.0 Size=24.0 Thre=2.0; Atmosphere Dens=0.394 Haze=10.0 Glar=0.61; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Blur Size=0.0 |
| Zombie Outbreak Survival | ShadowMap | 3.0 | 14:30:00 | `#464646` | `#464646` | 1.0 | 1.0 | 0.0 | 0.2 | - |
| "Evade" (brainrot game) | ShadowMap | 2.0 | 14:00:00 | `#f1f1f1` | `#d4d4d4` | 1.0 | 0.5 | 0.0 | 0.2 | SunRays Inte=0.071 Spre=0.576; ColorCorrection Brig=0.1 Cont=0.1 Satu=-0.2 Tint=#ffe9e9; Atmosphere Dens=0.2 Haze=0.0 Glar=0.0; Atmosphere Dens=0.2 Haze=0.0 Glar=0.0 |
| Backrooms Exploration | ShadowMap | 0.0 | 14:30:00 | `#464646` | `#464646` | 1.0 | 1.0 | 0.0 | 0.2 | SunRays Inte=0.01 Spre=0.1; Atmosphere Dens=0.3 Haze=0.0 Glar=0.0; Bloom Inte=1.0 Size=24.0 Thre=2.0 |
| Tower Of Hell | Voxel | 3.1334 | 14:00:00 | `#8a8a8a` | `#808080` | 0.0 | 0.0 | 0.0 | 0.2 | Bloom Inte=0.0 Size=24.0 Thre=0.95 |
| RIVALS (modded) | Future | 3.0 | 12:00:00 | `#797979` | `#c6c6c1` | 1.0 | 1.0 | -0.15 | 0.5 | Blur Size=0.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Blur Size=0.0; Blur Size=0.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Blur Size=0.0; Blur Size=0.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Blur Size=0.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Atmosphere Dens=0.255 Haze=1.82 Glar=0.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff |
| The Rake (kill test) | ShadowMap | 2.0 | 14:00:00 | `#4b4b4b` | `#4b4b4b` | 0.0 | 0.0 | 0.23 | 0.1 | ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; SunRays Inte=4.0 Spre=1.0; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=-0.8 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff |
| Work at a Pizza Place | Voxel | 1.9812 | 07:50:00 | `#594b33` | `#ffcdb0` | 0.0 | 0.0 | 0.0 | 0.5 | ColorCorrection Brig=0.0 Cont=0.1 Satu=0.1 Tint=#ffecd5; SunRays Inte=0.2 Spre=1.0; Bloom Inte=0.0 Size=24.0 Thre=0.95 |
| Gore game (leak) | Future | 3.5 | 15:00:00 | `#64846c` | `#7f805d` | 0.5 | 1.0 | 0.0 | 0.02 | Atmosphere Dens=0.348 Haze=0.0 Glar=0.63; ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#e7fff3; DepthOfField FarI=1.0; SunRays Inte=0.126 Spre=0.147 |
| Catalogue Avatar Creator | ShadowMap | 3.0 | 14:30:00 | `#464646` | `#464646` | 1.0 | 1.0 | 0.0 | 0.2 | ColorCorrection Brig=0.0 Cont=0.0 Satu=0.0 Tint=#ffffff; Bloom Inte=1.0 Size=24.0 Thre=2.0; SunRays Inte=0.01 Spre=0.1; Atmosphere Dens=0.3 Haze=0.0 Glar=0.0 |

**Observed ranges for enabled post effects:**

- Atmosphere.Density: 0.0 - 0.43 (median 0.28) across 16
- Atmosphere.Glare: 0.0 - 10.0 (median 0.0) across 16
- Atmosphere.Haze: 0.0 - 10.0 (median 0.0) across 16
- BloomEffect.Intensity: 0.0 - 3.0 (median 0.75) across 16
- BloomEffect.Size: 0.0 - 44444.0 (median 24.0) across 16
- BloomEffect.Threshold: 0.0 - 5.0 (median 2.0) across 16
- BlurEffect.Size: 0.0 - 8.0 (median 0.0) across 14
- ColorCorrectionEffect.Brightness: 0.0 - 0.3 (median 0.0) across 44
- ColorCorrectionEffect.Contrast: 0.0 - 0.3 (median 0.0) across 44
- ColorCorrectionEffect.Saturation: -0.8 - 1.0 (median 0.0) across 44
- DepthOfFieldEffect.FarIntensity: 0.0 - 1.0 (median 0.27) across 5
- SunRaysEffect.Intensity: 0.0 - 4.0 (median 0.03) across 18
- SunRaysEffect.Spread: 0.1 - 1.0 (median 0.43) across 18

Technology used: {'ShadowMap': 17, 'Voxel': 8, 'Future': 5, None: 2, 'Compatibility': 2}

## 7. Model library

| Game | Models | Sets | Median instances / model | Median parts / model | MeshPart-heavy models | Characters | VFX | Tools+weapons |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| +1 Drill & Mine | 636 | 129 | 25.0 | 1.0 | 104 | 40 | 59 | 244 |
| +1 Shrink Keyboard Escape | 718 | 70 | 11.0 | 2.0 | 82 | 1 | 66 | 0 |
| BIG Paintball! Classic | 164 | 7 | 10.0 | 4.0 | 40 | 2 | 16 | 98 |
| Bee Swarm Simulator (remake) | 594 | 23 | 5.0 | 3.0 | 435 | 43 | 7 | 54 |
| Bite By Night | 1058 | 190 | 4.0 | 1.0 | 813 | 98 | 133 | 12 |
| Build a Raft & Sail | 37 | 3 | 3 | 1 | 0 | 0 | 0 | 9 |
| Driving Empire | 627 | 116 | 4 | 2 | 111 | 30 | 18 | 10 |
| Jujutsu Shenanigans | 1817 | 8 | 7 | 1 | 384 | 65 | 961 | 85 |
| One Piece: The Age Of Pirates | 116 | 1 | 4.0 | 1.0 | 0 | 3 | 0 | 42 |
| Pick a Side | 155 | 0 | 18 | 2 | 6 | 4 | 46 | 166 |
| The Dusty Trip (framework) | 4 | 0 | 3.5 | 1.0 | 0 | 0 | 0 | 1 |
| +1 NeeDoh Escape | 40 | 9 | 8.5 | 2.0 | 3 | 0 | 0 | 0 |
| Keyboard Trading V2 | 354 | 13 | 9.0 | 1.0 | 139 | 91 | 61 | 18 |
| Steal an Egg | 2104 | 66 | 8.0 | 5.0 | 943 | 359 | 272 | 121 |
| Animal Hospital | 315 | 15 | 11 | 4 | 112 | 70 | 4 | 29 |
| Pass The Bomb (Tower) | 15 | 4 | 5 | 1 | 3 | 1 | 0 | 0 |
| Doors (fully scripted) | 332 | 8 | 229.5 | 41.0 | 125 | 121 | 29 | 42 |
| Drive For Brainrots | 180 | 4 | 91.0 | 1.0 | 152 | 149 | 60 | 145 |
| Grow a Garden 2 (GAG2) | 455 | 1 | 12 | 5 | 78 | 47 | 38 | 32 |
| Mine A Brainrot | 513 | 36 | 8 | 4 | 44 | 69 | 12 | 11 |
| Murder Mystery 2 | 786 | 41 | 10.0 | 6.0 | 69 | 30 | 5 | 68 |
| Punching Simulator | 408 | 16 | 5.0 | 2.0 | 157 | 3 | 24 | 39 |
| Scooter Obby | 297 | 47 | 26 | 7 | 38 | 3 | 56 | 2 |
| Shattered Aether (map) | 106 | 31 | 2.0 | 1.0 | 92 | 0 | 1 | 0 |
| Steal a Brainrot | 9586 | 283 | 7.0 | 2.0 | 7187 | 1868 | 727 | 188 |
| Vergil (character kit) | 12 | 0 | 7.0 | 1.0 | 2 | 1 | 6 | 0 |
| Zombie Outbreak Survival | 62 | 3 | 12.0 | 5.0 | 17 | 5 | 1 | 14 |
| "Evade" (brainrot game) | 5234 | 158 | 5.0 | 2.0 | 3623 | 1041 | 427 | 176 |
| Backrooms Exploration | 12 | 1 | 171.0 | 45.5 | 0 | 1 | 0 | 1 |
| 100 Weapons Models (mtsowiks) | 477 | 0 | 2 | 1 | 240 | 0 | 115 | 478 |
| Forest Pack (slbr) | 56 | 0 | 4.0 | 1.0 | 55 | 13 | 1 | 0 |
| Tower Of Hell | 11 | 1 | 7 | 1 | 0 | 0 | 0 | 6 |
| RIVALS (modded) | 2423 | 41 | 8 | 4 | 1883 | 65 | 443 | 414 |
| The Rake (kill test) | 149 | 3 | 70 | 7 | 27 | 39 | 10 | 97 |
| Work at a Pizza Place | 538 | 30 | 6.0 | 2.0 | 1 | 23 | 2 | 23 |
| Gore game (leak) | 85 | 4 | 11 | 3 | 54 | 21 | 6 | 5 |
| Catalogue Avatar Creator | 26 | 9 | 3.5 | 2.0 | 5 | 2 | 2 | 0 |

## 8. Lobbies, spawns and hubs

Workspace folders or models named lobby, hub or spawn, measured as a whole (40+ parts). The matching packs are under `<game>/models/Workspace/...` with the same path.

| Game | Path in the place | Parts | Instances | MeshParts | Emitters | Lights | World GUIs | Sounds | Size (studs) |
|---|---|---:|---:|---:|---:|---:|---:|---:|---|
| RIVALS (modded) | `Workspace .Lobby` | 3395 | 7679 | 1515 | 174 | 69 | 355 | 0 | 2275x351x1446 |
| Murder Mystery 2 | `Workspace.Lobby` | 2005 | 3867 | 238 | 4 | 6 | 999 | 0 | 722x302x266 |
| Zombie Outbreak Survival | `Workspace.Lobby` | 999 | 4264 | 119 | 8 | 7 | 129 | 2 | 1608x1387x2703 |
| Bite By Night | `Workspace.Lobby` | 841 | 1819 | 617 | 9 | 34 | 35 | 18 | 88x525x398 |
| +1 Drill & Mine | `Workspace.Spawn` | 830 | 2619 | 0 | 393 | 1 | 51 | 0 | 136x52x185 |
| Keyboard Trading V2 | `Workspace.Lobby` | 561 | 1005 | 146 | 75 | 1 | 66 | 2 | 232x73x252 |
| +1 Shrink Keyboard Escape | `Workspace.Decorations.HUB` | 503 | 1359 | 136 | 5 | 0 | 122 | 0 | 219x51x1706 |
| +1 Shrink Keyboard Escape | `Workspace.World2.Decorations.HUB` | 503 | 1346 | 136 | 5 | 0 | 124 | 0 | 219x51x1706 |
| +1 Shrink Keyboard Escape | `Workspace.World3.Decorations.HUB` | 499 | 1342 | 136 | 5 | 0 | 124 | 0 | 219x51x1706 |
| One Piece: The Age Of Pirates | `Workspace.SpawnBox` | 105 | 106 | 0 | 0 | 0 | 0 | 0 | 22x20x22 |
| Pick a Side | `Workspace.Lobby` | 104 | 185 | 0 | 0 | 2 | 0 | 0 | 263x86x204 |
| Scooter Obby | `Workspace.Lobby` | 102 | 304 | 16 | 14 | 4 | 111 | 0 | 99x151x125 |
| Tower Of Hell | `Workspace.Storage.Lobby` | 76 | 85 | 0 | 0 | 0 | 0 | 0 | 102x16x102 |
