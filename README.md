Cross-fading LOD shader example
===============================

This example shows how to use the corss-fading feature in
[LOD Group](http://docs.unity3d.com/Manual/class-LODGroup.html)
which is availble from Unity 5.

![blend](https://38.media.tumblr.com/b11530c8fd4b8128974e0136c93538b6/tumblr_nqsju04NOo1qio469o1_400.gif)
![dither](https://38.media.tumblr.com/71ed4fe604bb37ac3b7b9a0ccda9c4ad/tumblr_nqsju04NOo1qio469o2_400.gif)

How to set up
-------------

- Set up the LOD Group in the usual manner.
- Change Fade Mode in the LOD Group to "Cross Fade".
- Set Fade Transition Width to a proper value, like 0.5.
- Change materials in the group to use one of the cross-fading LOD shaders.
