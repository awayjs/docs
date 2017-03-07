# AwayJS API Documentation
AwayJS is composed of a series of modules which implement specific functionalities, allowing for a very flexible configuration of feature sets.

* [Modules](#anchor_modules)
* [Installation](#anchor_installation)
* [Feedback](#anchor_feedback)

<a name="anchor_modules" class="anchor"></a>
## Modules

### [core](core/)
The root dependency for all AwayJS modules: contains basic data structures, loading mechanisms, event objects and utility functions useful for all types of rich media interface and interaction.

### [graphics](graphics/)
Dependency for AwayJS applications requiring graphical output: contains data structures for shapes and textures, and interface descriptions for additional APIs such as material and animator data.

### [scene](scene/)
Dependency for AwayJS applications requiring a heirarchical scenegraph: contains data structures for a collection of display object types, as well as geometric prefabs for simple 2D & 3D objects.

### [stage](stage/)
Interface for graphics module providing various outputs options to render. Contains context implementations for WebGL and Software (js) outputs, as well as a bridge option for external (native) rendering.

### [renderer](renderer/)
Interface for scene and material modules, providing simpified rendering for complex heriarchies.

### [materials](materials/)
Dependency for AwayJS applications requiring a configurable method for coloring / texturing / lighting the surfaces of objects: contains data structures for a collection of material types, as well as the rendering APIs (to be moved to renderer module).

### [player](player/)
Dependecy for AwayJS applications requiring scripting abstraction for different converted syntax trees such as AS2, AS3 etc.

### [view](view/)
Interface for scene modules, providing user interaction input / output and culling management for display objects sent to the renderer.

### [parsers](parsers/)
Temporary module to hold parsers that output classes spanning multiple modules. To be split and moved to their respective module location(s) once additional refactors are in place.

<a name="anchor_installation" class="anchor"></a>
## Installation

Please refer to the installation instructions found in
[awayjs-full](https://github.com/awayjs/awayjs-full).

<a name="anchor_feedback" class="anchor"></a>
## Feedback

Please let us know how you think this resource could be improved. We hear you!<br>
[Create an issue](https://github.com/awayjs/docs/issues).