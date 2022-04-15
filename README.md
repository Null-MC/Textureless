# Textureless
A Minecraft Resource Pack that fully relies on shader PBR rendering instead of using textures with baked-in lighting, while maintaining the Vanilla style. Requires [Optifine](https://optifine.net) and a shader that supports the LabPbr specification. Some recommendations are: Kappa, MollyVX, Complementary, BSL, Chocapic [PbrTest2], Loop.

## Releases
You can find them under _Assets_ in the [Releases](https://github.com/null511/MCRP-Textureless/releases) section.

**The LabPbr 32x release is the recommended version.**

|Release|Description|
|-|-|
|LabPbr-16x|A low-quality version using the original 16x texture resolution. Uses the full Lab PBR spec.|
|LabPbr-32x*|A standard quality version using 32x textures. Uses the full Lab PBR spec.|
|LabBakedAO-32x|A standard quality version using 32x textures. Uses the full Lab PBR spec, with the exception that AO has been baked into the albedo textures.|
|OldBakedAO-32x|A standard quality version using 32x textures. Uses the old PBR spec (required for SEUS shaders), with the addition of AO being baked into the albedo textures.|


| | | |
|-|-|-|
|<img src="https://github.com/null511/MCRP-Textureless/raw/main/media/Kappa-01.png" alt="Preview"></img>|<img src="https://github.com/null511/MCRP-Textureless/raw/main/media/Kappa-02.png" alt="Preview"></img>|<img src="https://github.com/null511/MCRP-Textureless/raw/main/media/Kappa-03.png" alt="Preview"></img>|
|<img src="https://github.com/null511/MCRP-Textureless/raw/main/media/Chocapic-01.png" alt="Preview"></img>|<img src="https://github.com/null511/MCRP-Textureless/raw/main/media/Chocapic-02.png" alt="Preview"></img>|<img src="https://github.com/null511/MCRP-Textureless/raw/main/media/MollyVX-01.png" alt="Preview"></img>|

## Editing

If you do not already have it, you will first want to download a copy of [PixelGraph](https://github.com/null511/PixelGraph/releases). Links to CLI and UI can be found under _Assets_. To avoid publishing repository resources, `~/src` is used as the root content directory.

## License
Licensed under Creative Commons Zero v1.0 Universal. You may freely use, modify, and redistribute this content.