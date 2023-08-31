# Maze Project

The Maze Project is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable environment.

The Maze Project was written in C using the SDL2 library. Development was performed using Ubuntu 14.04 LTS 

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award-winning catalog and many Humble Bundle games.

## Installation 
```sh
$ git clone https://github.com/TomLutherKE/maze_project.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera around (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![Maze Project Flowchart](https://i.imgur.com/hCT5D8l.png)

## Demo
[![The Maze Demo](https://i.imgur.com/VUtF0eT.png)]
