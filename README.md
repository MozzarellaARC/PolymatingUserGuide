# ***PolymatingUserGuide***
### _A page for user instructions and manuals_

Hello, MozzarellaARC here wants to give you a quick user guide for you to use Polymating.

Before we started, I want to give you the main point of using polymating:
1. Reference object
2. Retopology object
3. Operations / Operators

These 3 point will be explained later, for now let's take a look at the User Interface ( UI )

# _The UI_

![ui1](https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/be62331a-9e02-42c7-b2ce-a9f08d2e6040)

![ui2](https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/9a5ec593-ab9e-4110-9f21-93ca501aa6d0)

In Polymating 0.51.x the addon now has 2 main functionality which is the main operator that does the wrapping for retopology and overlay, The main button has different behavior from the previous versions of Polymating :
1. Polymating Operator will not stop automatically on different state of object visibility
2. Polymating Operator can now automatically gives material overlay to the selected mesh upon pressing "Start Polymating"

Please keep in mind that the overlay mechanics will overwrites existing materials, also the overlay mechanics has its own behavior :
1. Applying overlay will automatically turn on the state of "In Front", "Wireframe", "Backface Culling"
2. When using automatic "Apply on start", the overlay will not be removed automatically upon stopping Polymating
3. Please keep in mind.

Prety simple right, now that you know the ui. Let's take a closer look on a simple example how you can start retopology with Polymating!!

- - -

# _Reference mesh and Target mesh_

First off let's use Suzzane as a reference mesh and a random cube with subdivision as your target mesh, and create a new material to make it easier to see.

![SuzaneOnTop](https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/6b78647a-0e04-4dc8-a8e0-4031d8ae9b0c)

- - -

# _Overlay Material (not necessary)_

In 0.51.0 Polymating have overlay functionality to help the user fasten the material creation, but please keep in mind that the applying overlay will overwrites existing materials !!!, to use this features go to Edit > Preferences > Addon > Polymating . And then turn on the Experimental Feature toggle button to show the other settings.

![UI_3](https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/c2952aad-2def-4871-a4a2-cb4d786af984)

- - -

# _The Wrapping_
Ok Now the next part is kinda scary but, don't be afraid. Because if you have already experience retopologizing with Shrinkwrap Modifier before, then it would look similar, the below video is how the wrapping started when you are in the state of Polymating and this is where the magic happens.

Please keep an important note that the object that you selected will be your target mesh, Polymating will automatically stopped if the target is deselected / deleted / the reference object is remove from the picker manually when Polymating is running

https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/e1251adb-daeb-4499-8da9-abc4054f4f40

# The _Retopology_
Now that you have everything set, you can go to sculpt mode or edit mode whichever you prefer and then do the Retopology like this, also please pardon my retopology skill as this is just a quick show for you to understand. My actual Retopology skill is on another level hence the making of this addon xD, for this example I extensively use the sculpt grab and smooth tool :

https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/adb748e6-71ff-4e3e-9d3d-32122b9272e4

Now this is not the only way to use Polymating, one of the other way to use it is by using it in edit mode with the "Proportional Editing" turned on. Like this :

https://github.com/MozzarellaARC/PolymatingUserGuide/assets/62471068/873f3902-26b1-478a-b503-5643bc663667

But remember it was suppose to work with most of the Blender proprietary / primitive tool, so you could experiment with the other tool not mentioned on the guide. This guide just show which tool is mostly used by me.
_Have fun with the addon :D_

- - -
This addon is being used extensively for my other project The Rhine, which is a free model
https://sketchfab.com/mozzarellaARC/models
