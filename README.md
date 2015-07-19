# open-fuse-iso
Rapid image mounting/unmounting in userspace using fuseiso. Extensions: iso, img, bin, mdf, nrg.

This script is run on an image file and, depending on its state, it mounts/unmounts it to/from a folder of the same name + ".mount".

This little utility also has a desktop file for quick operation in a GUI. Set to deault it makes for double-click mounting/unmounting of image files. Mimetypes for compatible image files are:application/x-cd-image;application/x-raw-disk-image;application/octet-stream;

There are 2 versions of the script: ofi (uses notify-send) and ofit (CLI echo only)
