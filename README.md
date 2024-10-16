# Icy Shader for ME
To let MaterialEditor show corresponding options under this shader on its tab.
## Demonstration
https://youtu.be/1H1nK_7X3fE
## Options
### MainTex
The main texture of the object.
### BumpMap
The normal texture that makes bump effect on the surface of the object.
### Color
The base color. By default it is black to let ReflectColor and emission take place.
### ReflectColor
When using this shader, modders commonly import a cubemap into it. This ReflectColor manipulate the tint color the object's surface reflects the cubemap as a reflection probe.
### BumpStrength
It decides to what extent the normal texture affects in the rendering.
### EmissionStrength
It decides the brightness of light the object emits.
### Cutoff
If there is alpha channel used in the main texture, this option can cull the transparent or semi-transparent parts of the pattern.
### Alpha
It makes transparency of the object.
