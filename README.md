<!-- B9ProceduralWings_PBR v1.0.1 -->

# Presenting B9ProceduralWings PBR
RestockPBR support for B9ProceduralWings

# <img width="1920" height="1080" alt="purplePBR" src="https://github.com/user-attachments/assets/453d5924-20a2-4cb8-aabf-21a77a79f014" />

This mod adds support to B9ProceduralWings of the recoloring framework used by
[RestockPBR](https://forum.kerbalspaceprogram.com/topic/226940-wip-restockpbr-a-pbr-and-recolorable-conversion-for-restockrestock-alpha-6-june-25/).
Note **RestockPBR is not actually a dependency** --the framework is powered by Technicolor, and Resurfaced shaders.

## Features
- Brand new wing textures and materials, designed to seamlessly blend with RestockPBR's style.
- Tiled top and/or bottom variants for all B9-PW wings. [**Not in the B9-PW UI. right-click the part to switch variants**].
- Ability to recolor all of the above with the swatches included in Technicolor and in expansions such as
  [this](https://forum.kerbalspaceprogram.com/topic/231293-112x-technicolor-swatch-extensions-2026-07-07/).
- Backward and forward compatibility with "stock" B9-PW: your coloring/material choices for B9-PW wings are still saved if you later decide to uninstall the mod.

### [Some screenshots](https://imgur.com/a/b9proceduralwings-pbr-UwtVBaH) (using RestockPBR)

## Dependencies:
- [B9 Procedural Wings Fork](https://forum.kerbalspaceprogram.com/topic/203629-112-b9-procedural-wings-fork-modified/)
- Resurfaced, Technicolor and Shabby (the versions bundled with
  [RestockPBR 0.0.6](https://github.com/PorktoberRevolution/ReStockPBR/releases/tag/0.0.6), but no need for the RestockPBR folder that actually patches parts).
- [Deferred Rendering](https://github.com/LGhassen/Deferred/releases)
- ModuleManager

## Credits
This uses a very slighly modified version of the original B9-PW plugin in order to free the wings' materials --which are otherwise applied at runtime--, so they can be straightforwardly patched using Shabby.
Also included are versions of the B9-PW wing models with the surface meshes duplicated, as switching between bare/tiled variants is simpler when there are separate meshes with each material (texture).
When in-game, one can simply active/deactivate them.

**Credit of the models and code goes to all contributors to the B9ProceduralWings-Fork mod, which is currently maintained by linuxgurugamer.**

# 

### *B9ProceduralWings_PBR is distributed under MIT License*
<br>

*This mod was created without the use of any AI-generated code, text, textures or assets in general.*
