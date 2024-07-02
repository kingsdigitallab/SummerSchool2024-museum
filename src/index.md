---
layout: layouts/home.njk
---

<div class="illo-container">
  <img src="https://cdn.glitch.com/cad20829-cd7f-405a-95e8-5e17b206a304%2Fillustration.svg?v=1618198438357" class="illustration" style="align: right" alt="Eleventy!">
</div>

# RSE 2024 Summer school Day 2: KDL

## Example 1
## [Museum Virtual Tour](museum/example1)
### tamplate: museum.njk

This is a quick A-Frame example, creating a virtual tour for our museum activity and showing off a few of the features
of [A-Frame](https://aframe.io/).  We've made it with Glitch's 11ty template.

On desktop this can be controlled via the WASD keyboard controls with mouselook. On a mobile device look is tilt and joystick for movement.

Interaction examples are on the <a-box> (floating cube)

* Cursor responds to mouse over (look) by growing
* Box will change colour when observed.
* Clicking/touching while the cursor is on the cube will cause it to spin (an A-frame animation)


### Libraries used:

* [A-Frame](https://aframe.io/) 
* Navigation Mesh library from [aframe-xr-boilerplate](https://github.com/AdaRoseCannon/aframe-xr-boilerplate)
* Visual joystick from [Aframe-examples](https://github.com/stemkoski/A-Frame-Examples).


### Getting started (and things to do)

- First, remix this Glitch to make one of your own.
- You can edit this directly in browser, or clone the git repo of your new glitch, and run it locally with 11ty and node
- Add your own models and exhibit them in the space.  Look at our test cube for ideas about what to add to the component.
- There are only default lights in the scene.  Try turning them off and adding your own: [docs](https://aframe.io/docs/1.6.0/components/light.html)
- You can also add [audio](https://aframe.io/docs/1.6.0/components/sound.html) as well. 
 
## Example 2 
## [AR Example](museum/example2)
### template: mindar.njk
There are a few image tracking solutions for A-frame/Three.js.  
This example is made with [MindAR](https://hiukim.github.io/mind-ar-js-doc/) which also supports face tracking.  
It uses the [tractor](https://sketchfab.com/3d-models/old-tractor-ferguson-te20-604cb70b362846ba8a3e835bff65ae7b) made by [Fredrik Johanson](https://sketchfab.com/kird3rf)

Use the [Tractor image target](/public/assets/mindar/image-target.jpg) either printed out or on a screen.  
If you want to use your own image, run it through the [image processor](https://hiukim.github.io/mind-ar-js-doc/quick-start/compile) to create a .mind file, 
then change the imageTargetSrc attribute in the a-scene in the template.  To change the model, you can change the path in the a-asset element or add your own.

