
# Blender Geo Nodes

A collection of 8 nodes that you may use it in your project to make awesome effects.

# How to use the Geo Nodes

Add the blender file to your asset library and then you'll have access to them.





## Weld
#### Information
---
Drag the weld modifier from your library onto a cube this will be the object that provides the welding. Inside the welding modifier select two different objects.  Anywhere those two objects intersect the weld effect will generate.

> You can choose the weld material in the modifier.

Options | Description
--- | --- 
**Minimum**| `controls the minimum size range of the welding bubbles that appear ` 
**Maximum**| `controls the Maximumsize range of the welding bubbles that appear ` 

> Be careful with these if you go too far it can look bad.

## Screenshots

![App Screenshot](https://i.imgur.com/tmr0GMc.png)


## Rope
#### Information
---
Drag the modifier from your library onto a curve.  The rope effect will follow it so you can draw points and move them around for whatever you need.

> You can choose the weld material in the modifier.

Options | Description
--- | --- 
**Rope twists**| `changes the distance between the twists.` 
**thread thickness**| `changes the radius of its thread.` 
**Fray length**| `changes how long the fibers coming off the rope are.` 
**Thread material**| `change the individual threads materials.` 
**Fraying material**| `change the color of the fraying fibers` 

> The default rope material it comes with has ambient occlusion turned on to give the appearance of strings making up each thread.

Remnels Notes:
*  A higher number means further apart twists and lower makes the twists closer.  Anything below 1 starts to look jagged for the rope twists.
* Use the thread thickness if you need a thinner or thicker rope.
* Set the fray length to 0 to have nice smooth rope.
* Thread material is useful if you want ropes made out of metal, webbing or vines.

## Screenshots

![App Screenshot](https://i.imgur.com/k0V1RUJ.png)
