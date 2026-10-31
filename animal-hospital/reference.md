# Animal Hospital: quality reference

Numbers measured from the place file. Use them as targets when building something in this genre.

## UI

- 26 ScreenGuis, 353 GUI objects, 47 unique images
- Fonts: `Silkscreen Regular`×20 `Noto Serif SC Bold`×20 `Noto Serif SC Regular`×17 `Fuzzy Bubbles Bold`×13 `Inconsolata Regular`×8 `Inconsolata Bold`×8
- Panel colours: `#000000`×35 `#ffffff`×8 `#787a81`×3 `#db4aff`×2 `#121212`×2 `#1c1c28`×1 `#ffe228`×1 `#fffb00`×1 `#2dd20b`×1 `#ff0000`×1
- Text colours: `#ffffff`×58 `#000000`×23 `#ff2600`×10 `#b2b1b3`×4 `#009202`×4 `#1b2a35`×4
- Stroke colours: `#000000`×67 `#ffffff`×8 `#000a01`×4 `#00f900`×2 `#cfcfcf`×1; thickness `1.0 px`×39 `2.0 px`×34 `5.0 px`×4 `3.0 px`×3 `1.5 px`×1
- Corner radius: `{0.5,0}`×7 `{0.25,0}`×3 `{1.0,0}`×2 `{0.0,10}`×1 `{0.0,5}`×1 `{0.02,0}`×1
- Size mode: {'scale': 330, 'mixed': 20, 'offset': 3}; TextScaled share 0.87; text sizes `14`×10 `8`×4 `20`×4
- Per 100 GUI objects: UICorner 4.5, UIStroke 23.2, UIGradient 9.1, UIAspectRatioConstraint 15.9, UIListLayout 4.0, UIGridLayout 0.0, UIPadding 8.2, UIScale 2.5, UITextSizeConstraint 5.1, ImageLabel 33.1, ImageButton 1.4, TextButton 3.7

## Map

- 7176 instances, 3765 parts (253 MeshParts, 34 unions); core extent [184, 18, 229] studs (X, Y, Z; 2nd-98th percentile), everything [1000, 59, 1000]
- Lights 56, particle emitters 17, beams/trails 3, textures/decals 187, SurfaceAppearance 7, world GUIs 219, prompts 120, sounds 280
- Materials: `SmoothPlastic`×1448 `Plastic`×845 `Metal`×498 `Concrete`×479 `Brick`×133 `Wood`×114 `Neon`×77 `Fabric`×38 `Material2306`×31 `WoodPlanks`×28
- Part colours: `#a3a2a5`×590 `#f8f8f8`×359 `#635f62`×343 `#1b2a35`×329 `#d1d1c1`×244 `#f2f3f3`×196 `#5b5d69`×176 `#cdcdcd`×157 `#9fa1ac`×132 `#95a4b3`×96 `#111111`×79 `#80bbdb`×56
- Terrain voxel data: 2 bytes

## Lighting

- Technology=ShadowMap, Brightness=0.0, TimeOfDay=20:00:00, Ambient=#91979d, OutdoorAmbient=#000000, ColorShift_Top=#616566, EnvironmentDiffuseScale=0.25, EnvironmentSpecularScale=0.25, ExposureCompensation=0.0, GlobalShadows=True, ShadowSoftness=0.2, FogEnd=100000.0, FogColor=#c0c0c0, GeographicLatitude=0.0
- **Atmosphere** `Atmosphere`: Color=#b4b4b4, Decay=#5a6473, Density=0.4, Glare=10.0, Haze=0.01, Offset=0.9
- **Sky** `DreamyOcean`: CelestialBodiesShown=True, StarCount=1000, SunAngularSize=21.0
- **BloomEffect** `Bloom`: Enabled=True, Intensity=1.0, Size=24.0, Threshold=2.0
- **BlurEffect** `Blur`: Enabled=True, Size=1.0
- **ColorCorrectionEffect** `ColorCorrection`: Brightness=0.0, Contrast=0.3, Enabled=True, Saturation=1.0, TintColor=#f3f2ff
- **DepthOfFieldEffect** `DepthOfField`: Enabled=True, FarIntensity=0.025, FocusDistance=0.05, InFocusRadius=50.0, NearIntensity=0.044
- **SunRaysEffect** `SunRays`: Enabled=False, Intensity=0.25, Spread=1.0
