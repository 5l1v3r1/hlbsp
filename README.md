Force: Leashed WebGL level viewer
======================================

This project loads and displays .bsp and .mdl files from the game Force: Leashed, using WebGL.

DEMO:
-----
http://www.kepuli.com/bspviewer/

**(Please note, the levels and textures might take a while to load)**

*Update 02.01.2012*
- removed WAD texture loading, using plain JPG images now (loading times improved vastly!)
- alpha mask textures support

NOTES:
- .bsp, .wad and .mdl files are loaded and processed as binary files
- some brush entities are not positioned correctly, this might require more sophisticated level parsing 

This viewer is based on Michael Domanski's work on [hlbsp](https://github.com/rein4ce/hlbsp).

Code was initially inspired by Brandon Jones's Quake2 viewer.
It uses gl-utils and js-struct libraries written by him, go, take a look!
https://github.com/toji



