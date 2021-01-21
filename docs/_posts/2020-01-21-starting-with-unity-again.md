---
layout: post
title: "Playing with unity"
---

Getting started in unity.

1. Installed the latest Long term release from unity hub.
2. Created a Universal render pipeline project
3. Delete the sample scene
4. Add floor

- Used a plane first, but that didn't show up in game. No idea why. TODO: figure out why
- Used a cube, the way I always did it.
- Reposition floor

1. Set the camera to orthographic, the near camera to -1000, and locked the viewport gizmo to orthographic
2. Did some research on what to set the camera size to, in orthographic projection:

  - Should set the size of the camera depending on my resolution: https://answers.unity.com/questions/526841/changing-ortho-cam-size-according-to-resolution.html , https://answers.unity.com/questions/923782/please-help-to-understand-orthographic-camera-size.html and https://docs.unity3d.com/ScriptReference/Camera-orthographicSize.html

7. Created a wall out of unity cubes. Played a bit with textures included in unity. Replaced cubes with larger walls
8. Rotated the floor to create the more traditional isometric perspective.
9. REposition camera to make sense in game
10. Add a sphere and a cube. Attach rigidbody to cube along with a script for basic character movement.

  - Took movement script from https://www.studica.com/blog/isometric-camera-unity as a starting point