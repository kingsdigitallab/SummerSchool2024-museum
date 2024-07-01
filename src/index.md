---
layout: layouts/home.njk
---

<div class="illo-container">
  <img src="https://cdn.glitch.com/cad20829-cd7f-405a-95e8-5e17b206a304%2Fillustration.svg?v=1618198438357" class="illustration" style="align: right" alt="Eleventy!">
</div>

# RSE 2024 Summer school Day 2: KDL

## Example 1
## [Museum Virtual Tour](museum/example1)

This is a quick A-Frame example, creating a virtual tour for our museum activity and showing off a few of the features
of A-Frame.  We've made it with Glitch's 11ty template.

On desktop this can be controlled via the WASD keyboard controls with mouselook. On a mobile device look is tilt and joystick for movement.

Interaction examples are on the <a-box> (floating cube)

* Cursor responds to mouse over (look) by growing
* Box will change colour when observed.
* Clicking/touching while the cursor is on the cube will cause it to spin (an A-frame animation)


### Libraries used:

* Aframe and Aframe-extras
* Navigation Mesh library from [aframe-xr-boilerplate](https://github.com/AdaRoseCannon/aframe-xr-boilerplate)
* Visual joystick from [Aframe-examples](https://github.com/stemkoski/A-Frame-Examples).

### Getting started

- First, remix this Glitch to make one of your own.
- You can edit this directly in browser, or clone the git repo of your new glitch, and run it locally with 11ty and node
 
## Example 2 
## [AR Example](museum/example2)

A quick adaptation from the [Aframe Example](https://aframe.io/blog/arjs3/) showing image tracking.  The library
also has marker and geo tracking, see the documentation for more examples.

There are a few image tracking solutions for A-frame/Three.js.  Another is [MindAR](https://hiukim.github.io/mind-ar-js-doc/) which also supports face tracking.

