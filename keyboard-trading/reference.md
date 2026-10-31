# Keyboard Trading V2: quality reference

Numbers measured from the place file. Use them as targets when building something in this genre.

## UI

- 16 ScreenGuis, 3141 GUI objects, 120 unique images
- Fonts: `Roboto Regular`×299 `Zekton Regular`×272 `GothamSSm Bold`×197 `GothamSSm Heavy`×151 `Roboto Light`×118 `SourceSansPro Regular`×98
- Panel colours: `#000000`×208 `#ffffff`×189 `#5e56d5`×124 `#1c1f25`×122 `#4b4b4b`×26 `#dddddd`×19 `#1d2e4d`×18 `#505050`×18 `#23272f`×16 `#464646`×16
- Text colours: `#ffffff`×833 `#000000`×314 `#c8c8c8`×70 `#dcdcdc`×42 `#969696`×40 `#e1e1e1`×34
- Stroke colours: `#000000`×429 `#ffffff`×39 `#540000`×22 `#00163a`×18 `#004202`×7 `#71043e`×7; thickness `0.06 scaled`×147 `0.04 scaled`×108 `0.05 scaled`×106 `0.07 scaled`×81 `0.1 scaled`×61
- Corner radius: `{0.0,4}`×274 `{0.2,0}`×120 `{0.1,0}`×120 `{0.0,6}`×82 `{0.05,0}`×46 `{0.5,0}`×29
- Size mode: {'scale': 3037, 'mixed': 62, 'offset': 38, 'zero': 4}; TextScaled share 0.77; text sizes `16`×272 `14`×36 `18`×18 `28`×11 `20`×6 `35`×4
- Per 100 GUI objects: UICorner 25.6, UIStroke 24.4, UIGradient 13.1, UIAspectRatioConstraint 20.9, UIListLayout 5.9, UIGridLayout 0.3, UIPadding 9.1, UIScale 0.2, UITextSizeConstraint 0.7, ImageLabel 14.1, ImageButton 4.6, TextButton 12.1

## Map

- 76847 instances, 40355 parts (37735 MeshParts, 308 unions); core extent [4848, 490, 153] studs (X, Y, Z; 2nd-98th percentile), everything [5050, 913, 963]
- Lights 13, particle emitters 48, beams/trails 44, textures/decals 466, SurfaceAppearance 34419, world GUIs 68, prompts 6, sounds 9
- Materials: `SmoothPlastic`×34430 `Plastic`×5894 `Sand`×16 `Neon`×7 `ForceField`×4 `Concrete`×4
- Part colours: `#9d8570`×6548 `#bc9f85`×6185 `#ffb27f`×6087 `#ffd8b5`×6042 `#a57452`×5830 `#c58862`×5755 `#a3a2a5`×3301 `#8c7662`×48 `#ffb07f`×45 `#ffb000`×29 `#b36a52`×26 `#111111`×25
- Terrain voxel data: 2 bytes

## Lighting

- Technology=ShadowMap, Brightness=2.06, TimeOfDay=14:00:00, Ambient=#7d7d7d, OutdoorAmbient=#464646, ColorShift_Top=#000000, EnvironmentDiffuseScale=1.0, EnvironmentSpecularScale=1.0, ExposureCompensation=0.0, GlobalShadows=True, ShadowSoftness=0.2, FogEnd=100000.0, FogColor=#c0c0c0, GeographicLatitude=0.0
- **SunRaysEffect** `SunRays`: Enabled=True, Intensity=0.01, Spread=0.1
- **Sky** `Sky`: CelestialBodiesShown=True, StarCount=1500, SunAngularSize=5.0
- **BloomEffect** `Bloom`: Enabled=True, Intensity=0.5, Size=24.0, Threshold=2.0
- **Atmosphere** `Atmosphere`: Color=#c7c7c7, Decay=#6a707d, Density=0.252, Glare=0.0, Haze=0.0, Offset=0.245
- **BlurEffect** `MenuBlur`: Enabled=True, Size=0.0
