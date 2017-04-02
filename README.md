DDMENU -- fork of dmenu-ee, fork of dmenu
=========================================

I've forked dmenu-ee and fixed a yoffset bug, as well as options:

- `-mh`, for setting menu height
- `-vf`, to implement [vertfull](http://tools.suckless.org/dmenu/patches/vertfull) patch programmatically
- `-so` for scrolloff capability (see [issue #3](https://github.com/toolpunk/dmenu-ee/issues/3) in dmenu-ee)
- `-cx`, `-cy`, `-c` options for centering
- `-e` to allow embedding dmenu to a window (all the above options work relative to parent window)

Original README is below.

dmenu-ee // dynamic menu extended edition
==============================
dmenu-ee is a fork of dmenu - an efficient dynamic menu for X, patched with XFT, quiet, x & y, token, fuzzy matching, follow focus, tab nav, filter and full mouse support.
Added an option to set the screen on which dmenu appears.
Also allows to dim screen with selected color and opacity while dmenu-ee is running.


Requirements
------------
In order to build dmenu-ee you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu-ee is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu-ee
(if necessary as root):

    make clean install


Running dmenu-ee
-------------
See the man page for details.
