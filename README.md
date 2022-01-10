# dmenu

This fork of [dmenu](https://tools.suckless.org/dmenu/) is intended to apply the patch [Line height](https://tools.suckless.org/dmenu/patches/line-height/) to the original dmenu in order to be used with my Qtile configuration.

However, this fork can be used everywhere, as it only applies a patch to modify the height of the prompt.

The original README of the project is this one:
```
dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.

```
