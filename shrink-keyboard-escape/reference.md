# +1 Shrink Keyboard Escape: quality reference

Numbers measured from the place file. Use them as targets when building something in this genre.

## UI

- 1 ScreenGuis, 633 GUI objects, 48 unique images
- Fonts: `DenkOne Regular`×173 `DenkOne Bold`×49 `SourceSansPro Regular`×42 `GothamSSm Bold`×2 `GothamSSm Regular`×1
- Panel colours: `#ffc906`×55 `#ffffff`×27 `#ac7c42`×24 `#000000`×19 `#2f2f2f`×15 `#3f3f3f`×12 `#ff6658`×10 `#33ff1c`×10 `#91ff14`×8 `#4b0305`×7
- Text colours: `#ffffff`×187 `#000000`×39 `#989898`×5 `#1ce711`×3 `#59ff00`×2 `#c8c8d2`×2
- Stroke colours: `#000000`×314 `#462813`×58 `#a70000`×5 `#59ff00`×1; thickness `3.0 px`×93 `2.5 px`×64 `2.0 px`×53 `2.8 px`×28 `4.0 px`×25
- Corner radius: `{0.0,8}`×120 `{0.0,3}`×60 `{1.0,0}`×15 `{0.0,12}`×1 `{0.0,0}`×1
- Size mode: {'scale': 622, 'zero': 2, 'offset': 8, 'mixed': 1}; TextScaled share 0.85; text sizes `14`×39
- Per 100 GUI objects: UICorner 31.1, UIStroke 59.7, UIGradient 4.9, UIAspectRatioConstraint 35.7, UIListLayout 2.4, UIGridLayout 0.2, UIPadding 0.3, UIScale 0.2, UITextSizeConstraint 0.0, ImageLabel 21.6, ImageButton 5.5, TextButton 8.2

## Map

- 16110 instances, 3969 parts (711 MeshParts, 3 unions); core extent [8190, 36, 1651] studs (X, Y, Z; 2nd-98th percentile), everything [8247, 57, 1722]
- Lights 0, particle emitters 312, beams/trails 24, textures/decals 8625, SurfaceAppearance 0, world GUIs 351, prompts 4, sounds 0
- Materials: `Plastic`×3666 `Fabric`×234 `Neon`×48 `Slate`×18 `SmoothPlastic`×3
- Part colours: `#8b4600`×504 `#606d71`×376 `#641c71`×316 `#a3a2a5`×266 `#773b88`×266 `#5e6088`×193 `#214b0a`×189 `#00af00`×178 `#000000`×120 `#ffff00`×99 `#57a5a2`×96 `#a564a4`×84
- Terrain voxel data: 2 bytes

## Lighting

- Technology=ShadowMap, Brightness=3.0, TimeOfDay=14:00:00, Ambient=#787878, OutdoorAmbient=#a5a5a5, ColorShift_Top=#e6ebff, EnvironmentDiffuseScale=1.0, EnvironmentSpecularScale=1.0, ExposureCompensation=0.1, GlobalShadows=True, ShadowSoftness=0.2, FogEnd=100000.0, FogColor=#c0c0c0, GeographicLatitude=0.0
- **ColorCorrectionEffect** `ColorCorrection`: Brightness=0.05, Contrast=0.0, Enabled=True, Saturation=0.0, TintColor=#fffaf5
- **Sky** `Sky`: CelestialBodiesShown=True, StarCount=3000, SunAngularSize=11.0
- **SunRaysEffect** `SunRays`: Enabled=True, Intensity=0.08, Spread=0.9
- **BlurEffect** `PopupBlur`: Enabled=True, Size=0.0
- **DepthOfFieldEffect** `DepthOfField`: Enabled=False, FarIntensity=0.1, FocusDistance=0.05, InFocusRadius=30.0, NearIntensity=0.75
- **Atmosphere** `ActiveAtmosphere`: Color=#dcebff, Decay=#787878, Density=0.22, Glare=0.0, Haze=0.0, Offset=0.0
