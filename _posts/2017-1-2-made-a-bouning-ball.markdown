---
layout: post
title:  "My first animation"
date:   2017-1-2
---
# My first animation
It is a bouncing ball that stays in place.<br>
The ball is blue, and the ground is white.

#### Timeline
So first I made a ball and floor.<br>
Then I raised the ball to its apex point.

Then I read [this](https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro/Basic_Animation/Lattice#Why_would_I_animate_the_object_too.3F),
which said that if a lattice deformer modifies an object, then moving said object will result
in the deformer applying after the transformation.

So I added a Lattice and parented the ball to it, choosing the Lattice deformer. <br>
[![Lattice deformer added](/assets/2017-1-2/Initial.png)](/assets/2017-1-2/Initial.png)

So when the ball gets close to the ground it deforms, but at its apex it doesn't deform.<br>
[![Ball Deformation](/assets/2017-1-2/Deform.png)](/assets/2017-1-2/Deform.png)<br>

So now I just key frame and loop by repeating the previous keyframes.
Until I learned that there is a Make Cyclic, under Extrapolation Mode in the Channels menu, all in the Animation screen layout.<br>
Then I rendered using Cycles Engine.

This whoie endevaour took me two days to accomplish. <br>
Though this is because I had to learn to use blender. <br>

#### Future
I think I will try to make this using a program, next time.
I think it will go a lot slower, since I haven't learned the blender python3 api. 

#### Video
<video width="720" controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video> 