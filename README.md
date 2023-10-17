# io_scene_obj_modelio

This is a fork of Blender's OBJ importer that adds support for most of the PBR directives that Model I/O and [USDConverter](https://github.com/SamusAranX/USDConverter) use.

The original documentation can be found here: https://docs.blender.org/manual/en/3.6/addons/import_export/scene_obj.html

This version of the addon has had its export functionality removed. Exporting models with Model I/O .mtl directives is out of scope for this project.

There are two other changes in the Material generator:
* Generated Texture nodes use Cubic interpolation by default
* Principled BSDF nodes use Multiscatter GGX by default