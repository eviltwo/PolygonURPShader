# PolygonURPShader
 Custom URP shader for synty material. (Nature biomes series)
 
 **This is unofficial asset.**

The shader included in the Nature biomes series sold by Synty Studio has some problems with URP. 
- LOD boundaries flicker in built game.
- Rocks and trees flicker when changing Rendering path to Forward+.

Synty studio seems to be aware of this problem, but I can't wait for it to be fixed, so I created a similar custom shader using ShaderGraph.
| Synty shader | Custom shader | Useage | Comment |
| --- | --- | --- | --- |
| SyntyStudios_Triplanar_Basic | PolygonURP_Triplanar_Basic | Rocks and grasses | |
| SyntyStudios_VegitationShader | PolygonURP_VegitationShader_NoWind | Trees and bushes | No wind |

# Sample image
Forward and Forward+ sample.
Left:Synty shader, Right: custom shader
![PolyURP](https://github.com/eviltwo/PolygonURPShader/assets/7721151/a23877e2-40f8-4d6c-9a6e-e915f29a86d8)

# Settings
- Shader graph 14.0.7 or higher.
