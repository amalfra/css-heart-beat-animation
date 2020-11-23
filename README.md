CSS heart beat animation
=========================

A quick experiment to create beat animation on heart icon using CSS. It is implemented using CSS3 animations.

![screenshot](https://raw.githubusercontent.com/amalfra/css-heart-beat-animation/master/demo-anim.gif)

## How it works

The CSS required to add the effect(which are only few lines) are available in ```beat-animation.css``` file. 
It's just basic CSS animation and may help more the people getting started with animations in CSS.

* First we will define ```@keyframes``` rule which is used to define what styles the element will have at certain times of animation. 
The style that a frame of animation will apply to the element will be scale function of transformation property. So each frame of animation will scale the element size by defined factor.
* Now define the animation property with .25s duration and alternate direction. With ```alternate``` direction the animation is played forwards first, then backwards. This way in one frame the element will be size will be scaled up(forward) and in next the size will be scaled down(backwards). The animation iteration count will be defined as infinte so that this keeps looping. Thus it will create the effect of beating.

## Development

Questions, problems or suggestions? Please post them on the [issue tracker](https://github.com/amalfra/css-heart-beat-animation/issues).

You can contribute changes by forking the project and submitting a pull request. Feel free to contribute :heart_eyes:

UNDER MIT LICENSE
=================

The MIT License (MIT)

Copyright (c) 2017 Amal Francis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
