Cross-fading LOD shader example
===============================

This example shows how to use the cross-fading option of [LOD Group] with
custom shaders.

![blend](https://i.imgur.com/7WZm3GH.gif)
![dither](https://i.imgur.com/z5qAtPm.gif)

[LOD Group]: http://docs.unity3d.com/Manual/class-LODGroup.html

How to set up
-------------

- Set up [LOD Group] in the usual manner.
- Change Fade Mode of the LOD Group to "Cross Fade".
- Set Fade Transition Width to a proper value, like 0.5.
- Update materials in the group to use one of the cross-fading LOD shaders.
