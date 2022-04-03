# Ray-tracer-mac

## Description
Общее описание
Что такое рейтрейсер

Description (from subject)
```
The goal of your program is to generate images using Raytracing protocol. Those computer generated images will each represent a scene, as senn from a specific angle and position, defined by simple geometric objects, and each with its own lighting system.
```

Allowed functions
```
open, close, read, write, malloc, free, perror, strerror, exit, math library (math.h), [mlx](https://harm-smits.github.io/42docs/libs/minilibx/introduction.html) (simple window creation library)
```

Fugures
```
plane, sphere, cylinder, square, and triangle
```

bmp file: No library allowed to create bmp file
show result using mlx library or create bmp file (no need mlx library)

config file

Example
```
c	 -50,0,30		    1,0.5,0		100
l     -40,0,30				0.7				                  255,255,255

pl	0,0,0			      0,1.0,0						          255,0,225
sp	0,0,20					20				255,0,0
sq	0,100,40		    0,0,1.0		30				        42,42,0
cy	50.0,0.0,20.6	  0,0,1.0 	14.2	    21.42	  10,0,255
tr	10,20,10		    10,10,20	20,10,10		      0,0,255
```

Описание структуры проекта

How to build
requirements: gcc, make

To build an executable run make command in root (of a project) folder

How to use
Executable arguments
1 - file with .rt extension containing scene description.
2 - "--save" key implements saving of the rendered scene to file with .bmp extension ("--save" is an optional argument).




