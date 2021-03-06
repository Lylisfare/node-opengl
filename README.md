# node-opengl (OpenGL bindings for node.js)

## 0. Notes

This package is a companion to the [node-sdl](https://github.com/creationix/node-sdl) package. It was built so the
OpenGL bindings for SDL could remain separate from the SDL library.

If you are looking for something else try the
[node-webgl](https://github.com/pufuwozu/node-webgl) project.

## 1. Installation

This package depends on node-sdl and OpenGL/SDL libraries being present
on the target system. The following should get SDL installed on Ubunutu:

<pre>sudo apt-get install libsdl-mixer1.2-dev libsdl-image1.2-dev libsdl-ttf2.0-dev</pre>
