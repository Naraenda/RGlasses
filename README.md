# RGlasses

RGlasses are a set of cool glasses (duh) that are to be worn as an accessory for a [VRChat](vrchat.com) avatar. The glasses are inspired by a cool DJ named [Rezz](https://en.wikipedia.org/wiki/Rezz). Please give her music a listen, it's very cool.

## Preview
Click on it to view it in HD on YouTube.

[![Example on youtube.](https://giant.gfycat.com/SleepyDistantBarasingha.gif)](https://youtu.be/BeIwJVz6WD0)

## Rules

You are **always allowed** to use this asset in **any** the following ways:

- For any non-VRChat related work, commercialy and non-commercialy, on the condition that both Rezz and me are credited.
- For a personal and private VRChat avatar as an accessory. No credits required.
- For a non-commercial public VRChat avatar as an accessory, on the condition that the [performance ranking](https://docs.vrchat.com/docs/avatar-performance-ranking-system#section-pc-limits) of said avatar is not "very poor". No credits required.
- For any commercialy VRChat avatar as an accessory, on the condition that the performance ranking of said avatar is not "very poor" and not "poor". No credits required.

For any other use, please contact me. I don't bite :)

---

## How to use

Download this repo as a zip and follow guide for either the Unity edition or Blender edition. If you have any problems, you can contact me on Discord `Narnia#ʘO∅1`.

### Unity

The Unity version is more for prototyping and a quicker way to get the glasses on (gotta make it before that rave tonight.), but it has a worse impact on the performance ranking than the other method. This is because it uses an extra skinned mesh renderer and requires one extra material slot.

1. Import the unity package.
2. Move the glasses so it aligns with your eyes.
    - You can use the blendshapes to change the dimensions of the frame if they don't fit just right.
3. In the object hierarchy, make the head of your avatar's armature the parent of the glasses.
4. Make your own animations, since the example one is boring. Use the blendshapes to enable and disable LEDs. You can make them turn on and off instantly by setting both tangents of a key to constant.
    - Don't forget to setup a transition from your animation to itself in the animation controller.
    - You can also animate the color! Please refer to the example.
5. When you're happy, you can upload it to VRChat.

### Blender

Using the blender version is preferred since you will be joining the mesh from the glasses with your own model so it shares the same skinned mesh renderer.

1. Ensure your model already has been texture atlased.
2. Add the glasses to your mesh and merge them with CATS Blender Tool.
3. Edit your atlasses for the frame of the glasses. You might want to peek at the UV mapping to see how everything is placed.
    - Optionally, if already are using emmision en alpha textures, you can also move the UV maps from the LEDs. If you do it like this, you won't need any extra materials at all and **have no performance impact!**
4. Scale and move the UV coordinates from the glasses to fit the part of the texture you just made.
5. Export everything to Unity, and do the animations. See step 4 from the Unity guide.

### Donate

If you like it, please buy me some hot chocolate.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O4O41M0YU)
