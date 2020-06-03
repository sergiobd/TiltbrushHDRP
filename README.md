# TiltbrushHDRP

These shader graphs allow you to import Tiltbrush sketches in Unity HDRP. Brushes that are implemented as surface shaders don’t work out of the box in HDRP with the Tiltbrush Unity SDK (e.g. TaperedFlat). Shaders that are implemented as fragment shaders _do work_. 

1. Download and import the Tiltbrush Unity SDK from their [release page](https://github.com/googlevr/tilt-brush-toolkit/releases).

1. Add the ShaderGraph assets to your project. Adding them to the project should be enough to see them available in the shader list (under ShaderGraphs>TiltbrushXXX)

1. Add a Tiltbrush sketch to your hierarchy

1. Change the material’s shader to ShaderGraph>TiltbrushXXX

1. Make sure to drag the texture and normal map from the original material too if the material is supposed to have one.

1. Edit the shader graph to your will, as well as the material’s properties (e.g. smoothness, metallic, alpha clip)

Disclaimer:

I made these shader graphs in order to visualize the sketches in Unity, but I did not care too much about making them look exactly as they do in Tiltbrush. You may have to edit the materials, shader graph and lighting settings of your scene if you want that.
