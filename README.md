# plant-visual-preview

Generated preview builds of the Plant3D interactive plant layouts.
Nothing here is source: each `.html` is a single self-contained WebGL bundle
produced by `build.py` in the (private) `plant_visual` repository.

Live: https://igorkant.github.io/plant-visual-preview/

| Page | Layout |
| --- | --- |
| `dle.html` | Continuous direct lithium extraction plant |
| `dle-1000.html` | Continuous DLE plant sized for 1000 m³/d of 50 ppm brine |
| `dle-pilot.html` | DLE pilot unit, 32 m³/h — ten radial columns in two banks, all-manual valving |
| `leadlag-pilot.html` | Lead-lag DLE pilot, 2 m³/h — two lead→lag pairs of 10 kg radial columns |
| `leadlag-skid.html` | Lead-lag DLE skid, 20 m³/h — five pairs of 2 m columns on one skid |
| `leadlag-system.html` | Lead-lag DLE system, 200 m³/h — ten identical skids off two headers, brine pumps 2 + 1 |
| `pontoon.html` | Floating sorption skid — four radial columns on a moored pontoon |
| `demo.html` | Reference scene covering the archetype library |

Append `?pid=1` to any page for the 2D P&ID view.
