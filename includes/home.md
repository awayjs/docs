# AwayJS API Documentation

AwayJS is composed of a series of modules which implement specific functionalities, allowing for a very flexible configuration of feature sets.

# Modules

## [@awayjs/core](core/)
The root dependency for all AwayJS modules: contains basic data structures, loading mechanisms, event objects and utility functions useful for all types of rich media interface and interaction.

## [@awayjs/graphics](graphics/)
Dependency for AwayJS applications requiring graphical output: contains data structures for shapes and textures, and interface descriptions for additional APIs such as material and animator data.

## [@awayjs/materials](materials/)
Dependency for AwayJS applications requiring a heirarchical scenegraph: contains data structures for a collection of display object types, as well as geometric prefabs for simple 2D & 3D objects.

## [@awayjs/parsers](parsers/)
Interface for graphics module providing various outputs options to render. Contains context implementations for WebGL and Software (js) outputs, as well as a bridge option for external (native) rendering.

## [@awayjs/player](player/)
Interface for scene and material modules, providing simpified rendering for complex heriarchies.

## [@awayjs/renderer](renderer/)
Dependency for AwayJS applications requiring a configurable method for coloring / texturing / lighting the surfaces of objects: contains data structures for a collection of material types, as well as the rendering APIs (to be moved to renderer module).

## [@awayjs/scene](scene/)
Dependecy for AwayJS applications requiring scriopting abstraction for different converted syntax trees such as AS2, AS3 etc.

## [@awayjs/stage](stage/)
Interface for scene modules, providing user interaction input / output and culling management for display objects sent to the renderer.

## [@awayjs/view](view/)
Temporary module to hold parsers that output classes spanning multiple modules. To be split and moved to their respective module location(s) once additional refactors are in place.