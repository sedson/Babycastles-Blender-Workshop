## Building 3D Worlds in Blender

February 14, 2021

Seamus Edson (he/him)

@worm_pilled

@rustforms


## Overview

Turn an idea into a world. This workshop is a rapid-fire introduction to making 3D environments from scratch with Blender. We will take an artist-friendly approach as we walk through a variety of tools and workflows.


## Lesson Plan

1. Install Blender + settings
1. Interface and 3D Viewport
1. Make Meshes
1. Model some basic *stuff*
1. Use modifiers to make a terrain
1. Populate terrain with particle systems
1. Add color with materials and lights
1. Place a camera and make a render
1. Shaders Editor


## Note on difficulty

This is meant to be a friendly introduction to *many* workflows in Blender. We are not going to go super in depth on any one topic. I will try to avoid too much jargon.


## Installing Blender

https://blender.org


**Settings to get started**

Edit > Preferences (CMD + ,)
- If using trackpad: Input >  Emulate 3 Button Mouse
- Navigation > Walk (disable Gravity)


## Some hot keys

| Key        | Action                          |
| ---------- | ------------------------------- |
| TAB        | Toggle Object/Edit Mode         |
| N          | Toggle info panel               |
| A          | Select all                      |
| Option + A | Deselect all                    |
| Shift + A  | Create new (depends on context) |
| G          | Grab (move)                     |
| R          | Rotate                          |
| S          | Scale                           |
| Shift + D  | Duplicate                       |
| Shift + C  | Reset 3D cursor                 |


## Blender Interface

- Tools down the left side
- Menus and workspaces along the top
- Big 3D viewport in the middle
- Scene view on top right
- Object Properties on bottom right


## Navigating the 3D view

- Left click to select objects
- Middle mouse button to rotate around view
  - Option + left click on trackpad
- Shift + middle mouse to pan through view


## Object vs Edit mode

- Object Mode is course -- I can manipulate objects as a whole by moving, rotating, and scaling
- Edit Mode is fine -- I can edit the internal data of any object
- Select objects with left click and toggle into/out of Edit Mode with TAB


## Make Meshes

- In Object mode:
- Shift + A -> choose your base mesh
- Practice moving, rotating, and scaling it
- Use TAB (or Menu to go into Edit Mode) and mess with the vertices, edges, and faces
