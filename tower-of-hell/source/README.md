# SLBR - Booster - Tower Of Hell

Source: `C:/Users/wnott/Downloads/need_unpack/SLBR - Booster - Tower Of Hell.rbxl`  
2459 instances, 100 classes, 67 scripts (2397 lines), 16 remotes, 60 asset ids

## Top level

| Service / root | Class | Descendants | Scripts (server/client/module) |
|---|---|---:|---|
| Workspace | Workspace | 256 | 3/0/0 |
| TextChatService | TextChatService | 3 |  |
| StarterPlayer | StarterPlayer | 4 | 0/2/0 |
| StarterGui | StarterGui | 389 | 1/16/0 |
| InsertService | InsertService | 1 |  |
| ReplicatedStorage | ReplicatedStorage | 25 |  |
| ServerScriptService | ServerScriptService | 20 | 7/2/0 |
| ServerStorage | ServerStorage | 1707 | 7/23/6 |
| Lighting | Lighting | 3 |  |

(42 empty services not listed)

## Key containers

**ServerScriptService** (7 children)

- Script `Leaderboard` -> `scripts/ServerScriptService/Leaderboard.server.luau`
- Script `MutatorScript` -> `scripts/ServerScriptService/MutatorScript.server.luau`
- Script `AdminScript` -> `scripts/ServerScriptService/AdminScript.server.luau`
- Script `ServerScript` -> `scripts/ServerScriptService/ServerScript.server.luau`
- Script `NoPlayerCollision` -> `scripts/ServerScriptService/NoPlayerCollision.server.luau`
- Script `Script` -> `scripts/ServerScriptService/Script.server.luau`
- Script `StatChanger` (13) -> `scripts/ServerScriptService/StatChanger.server.luau`

**ServerStorage** (7 children)

- Folder `AdminCommands` (5)
- Folder `Gears` (115)
- Folder `AdminModules` (1)
- Model `Template` (74)
- Folder `Stages` (900)
- Folder `UsedGuis` (604)
- Folder `PlaceIds` (1)

**ReplicatedStorage** (13 children)

- Folder `Mutators` (6)
- NumberValue `Minutes`
- BoolValue `MultiplierVisible`
- NumberValue `Multiplies`
- NumberValue `Seconds`
- NumberValue `TimerSpeed`
- StringValue `TimerTag`
- NumberValue `TowerHeight`
- RemoteEvent `DoorMessage`
- RemoteEvent `MutatorEvent`
- Folder `MutatorEvents` (6)
- RemoteEvent `HeightEvent`
- RemoteEvent `Stat`

**ReplicatedFirst** (0 children)


**StarterPlayer** (2 children)

- StarterPlayerScripts `StarterPlayerScripts`
- StarterCharacterScripts `StarterCharacterScripts` (2)
- LocalScript `SpeedScript` -> `scripts/StarterPlayer/StarterCharacterScripts/SpeedScript.client.luau`
- LocalScript `KillBrickScript` -> `scripts/StarterPlayer/StarterCharacterScripts/KillBrickScript.client.luau`

**StarterGui** (6 children)

- LocalScript `DoorMessage` -> `scripts/StarterGui/DoorMessage.client.luau`
- ScreenGui `MutatorGui` (5)
- ScreenGui `TimerGui` (3)
- ScreenGui `HeightGui` (9)
- ScreenGui `MobileShiftlock` (3)
- ScreenGui `ShopGui` (363)

**StarterPack** (0 children)


**Workspace** (7 children)

- Camera `Camera`
- Terrain `Terrain` (1)
- Folder `Songs` (5)
- Folder `Tower`
- Part `WinTp`
- Folder `Storage` (240)
- SpawnLocation `SpawnLocation` (3)

## UI roots

- LocalScript `DoorMessage` (0 descendants)
- ScreenGui `MutatorGui` (5 descendants)
- ScreenGui `TimerGui` (3 descendants)
- ScreenGui `HeightGui` (9 descendants)
- ScreenGui `MobileShiftlock` (3 descendants)
- ScreenGui `ShopGui` (363 descendants)
- ScreenGui `StatChanger` (12 descendants)
- ScreenGui `ShopGui` (402 descendants) [disabled]

## Largest scripts

- 382 lines, server: `scripts/ServerStorage/Gears/Hook/Script.server.luau`
- 169 lines, client: `scripts/ServerStorage/Gears/Hook/LocalScript.client.luau`
- 142 lines, server: `scripts/ServerScriptService/ServerScript.server.luau`
- 139 lines, client: `scripts/ServerStorage/UsedGuis/ShopGui/Frame/LocalScript.client.luau`
- 138 lines, client: `scripts/StarterGui/ShopGui/Frame/LocalScript.client.luau`
- 120 lines, client: `scripts/StarterGui/MobileShiftlock/LocalScript.client.luau`
- 92 lines, server: `scripts/ServerStorage/Gears/Trowel/WallMaker.server.luau`
- 82 lines, server: `scripts/ServerStorage/Gears/GravityCoil/GravityCoilScript.server.luau`
- 80 lines, server: `scripts/ServerStorage/Gears/FusionCoil/GravityCoilScript.server.luau`
- 71 lines, client: `scripts/StarterGui/MobileShiftlock/ImageButton/ShiftGUI.client.luau`
- 59 lines, server: `scripts/ServerStorage/Gears/FusionCoil/Script.server.luau`
- 58 lines, server: `scripts/ServerStorage/Gears/SpeedCoil/Script.server.luau`
- 41 lines, client: `scripts/ServerStorage/UsedGuis/ShopGui/Frame/ScrollingFrame/mutators/HighSpeed/LocalScript.client.luau`
- 39 lines, module: `scripts/ServerStorage/AdminCommands/coil.luau`
- 39 lines, module: `scripts/ServerStorage/AdminCommands/tp.luau`
- 35 lines, server: `scripts/Workspace/Storage/End/WinBrick/Script.server.luau`
- 34 lines, server: `scripts/ServerScriptService/MutatorScript.server.luau`
- 33 lines, server: `scripts/StarterGui/TimerGui/Script.server.luau`
- 33 lines, server: `scripts/ServerScriptService/NoPlayerCollision.server.luau`
- 32 lines, client: `scripts/StarterGui/HeightGui/LocalScript.client.luau`

## Scan

- Flags: 0 HIGH, 0 MED (details in flags.txt)
- Monetization ids in code: 6
- Scripts with decompiler headers: 0; empty scripts: 15

## Most common classes

- Part: 797
- StringValue: 206
- ImageLabel: 194
- TextLabel: 194
- Frame: 171
- Weld: 142
- BoolValue: 98
- ManualWeld: 79
- TextButton: 68
- Model: 67
- LocalScript: 43
- NumberValue: 32
- WedgePart: 32
- UIAspectRatioConstraint: 26
- TrussPart: 26
- Color3Value: 26
- IntValue: 19
- Script: 18
- Attachment: 17
- Sound: 15
- SpawnLocation: 13
- Folder: 12
- UIListLayout: 12
- RemoteEvent: 10
- UnionOperation: 8
