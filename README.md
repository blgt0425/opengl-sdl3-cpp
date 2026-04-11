Simple C++ project using SDL3, OpenGL (via GLAD), and GLM to render a rotating colored quad with basic controls.

You need these libraries installed:

* SDL3
* GLAD (OpenGL loader)
* GLM (math library)
* C++ compiler (MSVC / g++ / clang)

1. Install SDL3

Download SDL3 from the official site:

[https://github.com/libsdl-org/SDL](https://github.com/libsdl-org/SDL/releases/tag/release-3.4.4)

Then:

Extract it
Add include folder to your compiler include paths
Link the SDL3 library (SDL3.lib or .a depending on compiler)
2. Install GLAD

Generate GLAD here:

https://glad.dav1d.de/

Settings:

Language: C/C++
API: OpenGL
Version: 4.1 Core

Download and:

Put glad.c into your project
Add include/glad to your include path
3. Install GLM

Download:

https://github.com/g-truc/glm

Then:

Just include the glm folder (header-only library, no linking needed)

Include directories:
/path/to/SDL/include
/path/to/glad/include
/path/to/glm

Link libraries (example):
Windows (MSVC):
SDL3.lib
opengl32.lib

Linux:
-lSDL3 -lGL

🎮 Controls
Key	Action
W	Move forward
S	Move backward
A	Rotate left
D	Rotate right
R	Reset position

OpenGL version: 4.1
