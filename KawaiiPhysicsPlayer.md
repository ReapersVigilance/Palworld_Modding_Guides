# Kawaii Physics for Player Model Swaps
Using Unreal Editors Compatible Skeletons to add Custom Bones and apply physics to them

- **Written by: `ReapersVigilance`**




## Overview

This guide is to show how to setup your model with UE's compatible skeletons to activate Kawaii physics and collision. **FOR CUSTOM ADDED BONES** 
####
I am assuming you understand the concept and setup of model swapping including the extraction from FModel, Importing to Blender, Weight painting, and Export from Blender. I will touch on them briefly however.
Other guides are quite detailed in doing all of the above.

I'm going to Write this as a full Model Swap however it can be done with just Hair/Head Models as long as you use a dummy SK_PalHuman_Skeleton in the proper folder.

process is very similar to a normal model swap except for some key differences in the Exporting from blender and UE work.


### Critical Notes
- This method works for adding physics to **CUSTOM BONES** in both Hair and Head Swaps. It does **NOT** work for adding physics to Outfit swaps. (Unless you like T-posing everywhere)So it works best doing the two together and choosing which Kawaii parts will be Hair and which will be Head.
- As long as you're adding physics to Default Bones on an Outfit, that'll work without the Compatible Skeletons. Can skip right to the Kawaii section for that.
####
This is absolutely not a replacement for the bone reorder and animation tool by **`Shifty`**
It just allows you to add physics to swaps without breaking the animations.

Can be used in combination with Jiggle Physics (18+) guide by **`Dytser`**


### Tools Needed

- FModel
- Blender
- UE 5.1
- Kawaii Physics plugin 1.10
- UnrealPak


### Preview
![Gif_01-Preview.gif](assets/jiggle/Gif_01-Preview.gif)
