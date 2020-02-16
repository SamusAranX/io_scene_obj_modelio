# io_scene_obj_modelio

This is a fork of Blender's OBJ importer that adds support for most of the PBR directives that Model I/O and [USDConverter](https://github.com/SamusAranX/USDConverter) use.
It also takes the liberty of making all texture nodes use Cubic interpolation and making all Principled BSDF nodes use Multiscatter GGX instead of regular GGX.