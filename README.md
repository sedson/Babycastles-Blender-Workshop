![Cover](/cover.jpg)

## Building 3D Worlds in Blender

February 14, 2021

Seamus Edson

@worm_pilled

@rustforms


## Overview

Turn an idea into a world. This workshop is a rapid-fire introduction to making 3D environments from scratch with Blender. We will take an artist-friendly approach as we walk through a variety of tools and workflows.


## Lesson Plan

1. Setup
2. Interface and 3D viewport
3. Basic modeling
4. Make a terrain
5. Spawn objects with particle systems
6. Materials and lights
7. Placing camera and editing
8. Shader Editor


## Note on difficulty

This is meant to be a friendly (but fast-paced) introduction to many topics in Blender. We are not going to go super in depth on any one topic. Please tell me to slow down or speed up if need be.


## Setup

Edit > Preferences
- Input > Emulate 3 Button Mouse (if using trackpad)
- Keymap > Spacebar Action > Search


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


## Interface

The 3D Viewport is the large area in the center. There are tools for manipulating 3D objects on the left side. Pay attention to the gizmo that shows current orientation in the top right. Hit the (N) key to open an options panel.

The Outliner (top right) shows all the objects in the scene and lets you organize them into collections. We will use this feature in the second part of the workshop.

The Properties area (bottom right) exposes information and effects relating to each individual object.


## 3D Viewport

Left click to select objects.

Rotate view - middle mouse button to Option + left click on trackpad.

Scroll to zoom (mouse) or Command + Scroll (trackpad)

Shift + middle mouse to pan view;

(X) to delete. (Shift + A) to add a new objects.


## Object vs Edit mode

- Object Mode is course -- I can manipulate objects as a whole by moving, rotating, and scaling
- Edit Mode is fine -- I can edit the internal data of any object
- Select objects with left click and toggle into/out of Edit Mode with TAB


## Basic Modeling

In Object mode:
  - Shift + A -> choose your base mesh
  - There is a (usually closed) popup on the bottom left that has options for each base mesh
  - Practice moving, rotating, and scaling it

Use TAB (or Menu) to go into Edit Mode:
  - Mess with the vertices, edges, and faces
  - Play with Extrude (E) and Inset (I)

For this workshop, I am going to model two different kinds of things (rocks and trees) and make a couple variations of each. For the next steps to work, make sure to have each type of object inside its own collection (rock models in a rock collection). Create collections by right clicking in the Outliner (top right).

## Make a terrain

We can use a black and white noise texture to manipulate a flat plane and turn it into a 3D terrain.

In Object Mode:
  - Shift A -> Choose Grid
  - Open the additional options (bottom left) and choose something like 40 x 40 subdivisions
  - Select the grid and find the Modifiers Panel (blue wrench)
  - Use the Add Modifier Drop Down to add 2 Special effects to this terrain: Subdivision Surface and Displace
