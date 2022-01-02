# Project-fighter-jet
Here is the project about a mini game buit with c++ and openGL
In this program the Fighter Jet is drawn with the help of simple line code using GL_LINE_STRIP and GL_LINE_LOOP. The Jet also have shield. The activation also is control by user with keyboard function. 

If the shield flag is turn on, drawshield() function is called. This will then activate shield. The shield is not shaped like cg opengl circle but some what similar to it. With sine and cosine functions and GL_LINE_LOOP it get close to circle.

After Jet and Shield, next is bullet. In the Fighter Jet CG Programs in C GL_POINTS is used with for loop function to draw the bullet points. The entry flag set the entry point for bullet firing, allocate the bullet when to fire. The allocBullet function check if bullet is in use.
User Interaction Fighter Jet CG Programs in C
This cg Opengl program have keyboard interaction. Both alpha keys and navigation keys are allocated to the keyboard functions. 
ESC : Quit
S and s :
C and c : Show and Hide Cursor (More functionality is added by functions)
z and Z : Add 20 point in direction of motion.
f and F : Enter game mode.
x : Exit game mode
P and p : Pause the game
Q and q and Space : Fire bullet from fighter jet.

This cg opengl program have many keyboard functions. There are 4 keyboard functions  - key, keyup, special, specialup. 

Key function have the user interaction indicated above in the post. While in the Key function s, S setup the shield flag to one the same is set to keyup. Since different set of windows are created, it set the platform of shield and it's activation.  

The special and specialup function have up, left and right which give the thrust, left and right movement. 
