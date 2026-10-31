# Broken egg packs

Moved here on 2026-10-30. These Steal an Egg egg models use UnionOperations whose geometry was
lost when the live game was copied (TriangleCount 0 in Studio), so the egg body does not render;
only decorations such as the "?" signs remain. Folder layout mirrors `models/`.
Catalog entries point here and carry the tag `broken`.

- `ReplicatedStorage/Assets/Models/Eggs/` 21 eggs (dinos, brainrot "?" eggs, Eternal Lunar Dragon, Mosasaurus, ...)
- `ServerStorage/Assets/Models/Eggs/` the same 21 eggs (duplicates)
- `StarterPlayer/.../MonsterEvent/Cutscene/CutsceneVFX/Eggs/` 5 cutscene eggs (Penguin, Polar Bear, Walrus x2, Yeti)
