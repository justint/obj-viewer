# obj-viewer
[![Build Status](https://travis-ci.org/justint/obj-viewer.svg?branch=master)](https://travis-ci.org/justint/obj-viewer)

A simple one-file OBJ file viewer, written in C++ using OpenGL and GLUT.

## Usage

`$ obj-viewer bunny.obj`

Use the arrow keys to move the camera around/zoom in. Press `w` to enable
wireframe render mode, and `s` to switch back to the single light diffuse + 
specular light render mode. 

I threw in the classic Stanford bunny file for demonstrational purposes, but most other simple OBJ files should work. If you find an OBJ file that breaks my code, let me know so I can improve it!
