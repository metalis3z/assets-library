# The Dusty Trip (framework): quality reference

Numbers measured from the place file. Use them as targets when building something in this genre.

## UI

- 0 ScreenGuis, 0 GUI objects, 0 unique images
- Fonts: none
- Panel colours: none
- Text colours: none
- Stroke colours: none; thickness none
- Corner radius: none
- Size mode: {}; TextScaled share None; text sizes none
- Per 100 GUI objects: UICorner 0, UIStroke 0, UIGradient 0, UIAspectRatioConstraint 0, UIListLayout 0, UIGridLayout 0, UIPadding 0, UIScale 0, UITextSizeConstraint 0, ImageLabel 0, ImageButton 0, TextButton 0

## Map

- 37 instances, 15 parts (0 MeshParts, 1 unions); core extent None studs (X, Y, Z; 2nd-98th percentile), everything [2048, 28, 2048]
- Lights 1, particle emitters 0, beams/trails 0, textures/decals 2, SurfaceAppearance 0, world GUIs 0, prompts 0, sounds 2
- Materials: `Wood`×6 `Plastic`×6 `Metal`×2 `Ice`×1
- Part colours: `#a3a2a5`×5 `#6c584b`×4 `#69665c`×2 `#9fadc0`×1 `#dcbc81`×1 `#5b5b5b`×1 `#694028`×1
- Terrain voxel data: 2 bytes

## Lighting

- Technology=ShadowMap, Brightness=3.0, TimeOfDay=14:30:00, Ambient=#464646, OutdoorAmbient=#464646, ColorShift_Top=#000000, EnvironmentDiffuseScale=1.0, EnvironmentSpecularScale=1.0, ExposureCompensation=0.0, GlobalShadows=True, ShadowSoftness=0.2, FogEnd=100000.0, FogColor=#c0c0c0, GeographicLatitude=0.0
- **Sky** `Sky`: CelestialBodiesShown=True, StarCount=3000, SunAngularSize=11.0
- **SunRaysEffect** `SunRays`: Enabled=True, Intensity=0.01, Spread=0.1
- **Atmosphere** `Atmosphere`: Color=#c7c7c7, Decay=#6a707d, Density=0.3, Glare=0.0, Haze=0.0, Offset=0.25
- **BloomEffect** `Bloom`: Enabled=True, Intensity=1.0, Size=24.0, Threshold=2.0
- **DepthOfFieldEffect** `DepthOfField`: Enabled=False, FarIntensity=0.1, FocusDistance=0.05, InFocusRadius=30.0, NearIntensity=0.75
