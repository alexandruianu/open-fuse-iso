# open-fuse-iso
Rapid image mounting/unmounting in userspace using fuseiso.

This script passes is run on an image file and, depending on its state, it mounts/unmounts it to/from a folder of the same name + ".mount".

This little utility also has a desktop file for quick operation in a GUI.

There are 2 versions of the script: ofi (uses notify-send) and ofit (CLI echo only)
