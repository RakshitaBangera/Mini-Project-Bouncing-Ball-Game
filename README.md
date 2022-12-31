# Mini-Project-Bouncing-Ball-Game
A Ball game designed using C++ and Open GL

Introduction to OpenGL:
OpenGL is a cross-language, cross-platform application programming interface for rendering 2D and 3D vector graphics. 
The API is typically used to interact with a graphics processing unit, to achieve hardware-accelerated rendering
Most of the application will be designed to access OpenGL directly through functions
in three libraries. Functions in the main GL (or OpenGL in windows) library have names that
begin with the letters gl and are stored in a library usually referred to as GL (or OpenGL in
windows). The second is the OpenGL Utility Library (GLU). This library uses only GL
functions but contains code for creating common objects and simplifying viewing. All
functions in GLU can be created from the core GL library but application programmers prefer
not to write the code repeatedly. The GLU library is available in all OpenGL implementations;
functions in the GLU library begin with letters glu.
To interface with the window system and to get input from external devices into the
programs, need at least one more system-specific library that provides the “glue” between the
window system and OpenGL. For the X window system, this library is functionality that should
be expected in any modern windowing system.
For this window system, GLUT will use GLX and the X libraries. The application program,
however, can use only GLUT functions and thus can be recompiled with the GLUT library for
other window systems.
Description of the game:
In this, a ball is moving starting from the middle and goes to the up-
left corner colliding with the wall and changes direction following the
speed that was set by the player initially. Consequently, after colliding
with the wall ,the ball moves in a downward direction where it should
hit the rectangular base(slider) which is capable of moving in
horizontal direction.If the ball hits the slider then it bounces back up
to collide with some other wall and it will continue till it misses the
slider while coming down.The player has the control over the
slider,by which the player can hit the ball to bounce back up.

For working on Ubuntu operating system:
gcc filename.c -lGL -lGLU -lglut -lm
-where filename.c is the name of the file with which this program is
saved.

2.1 Game Rules
Ball should not miss the rectangular base (slider), if it does the game is over.

2.2 Procedure to Play

First the speed /level window will be displayed to select the level(speed) of the game.
The main output/gaming window will be displayed to start playing the game.
Use the keyboard (right and left )keys to operate the slider.
Use mouse to play and pause.
When the ball misses the rectangular base(slider),the game is over
