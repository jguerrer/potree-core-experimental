MIGRATION_STATUS

threejs version 0.181.2:   DONE. Everything is on newer version and renderer  context is on webgl2 with no further errors.

Shaders located in source/materials/shaders/ are already webgl2 compliant as they have webgl2 syntax and es300.

Canvas have to be identified for further querying and disposal

No references to old geometry, only buffer geometry.

Accepted loaders allow both multiple files and single formats.

The Viewer Class is no longer available, as that was the main rendering class. In this case is the custom class used for testing.

For compatibility, most functions available there should be made available and functions added as requried.
