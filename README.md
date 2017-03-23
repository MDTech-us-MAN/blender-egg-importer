This is an importer for Blender that can import .egg files.  It is designed to
be interoperable with YABEE and other Blender to Panda3D exporters, and aims
to preserve the hierarchical structure of the models.

In combination with the improved version of bam2egg available in development
builds of Panda3D, this also provides a reliable path to import .bam files
that are generated by egg2bam.

This is a Blender addon that does not require a Panda3D installation.

Most features supported by bam2egg are implemented.  In particular, however,
animation support is not yet finished.  Many other features still need to be
tested.

Supported features:
- .egg.pz and .egg.gz files
- Basic geometry
- All transform types
- Materials
- Textures
- Tags (as game properties)
- Collide and ObjectType (as game properties)
- Collision masks (as game properties)
- Coordinate system conversion

Yet to do:
- Improve performance of parser
- Triangle fans, strips, and lines
- NURBS surfaces and curves
- Morph targets
- Animations