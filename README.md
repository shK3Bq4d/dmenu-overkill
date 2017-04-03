DDMENU -- fork of dmenu-ee, fork of dmenu
=========================================

I've forked [dmenu-ee][] and fixed a yoffset bug, as well as implemented a completely customizable geometry, added switches for [vertfull][] and [scrolloff][] patches, and made dmenu embeddable while still allowing for customizable opacity and dimming (stock dmenu can embed with `-w`, but does not have opacity).

I've also added long options (`--option`) for every option.

dmenu-ee
--------

Dmenu-ee has itself added multiple features on top of the vanilla dmenu: XFT support, a quiet and a filter option, x and y offset, fuzzy matching, focus-following, tab navigation, full mouse support, and dimming and opacity customization.

[dmenu-ee]: https://github.com/toolpunk/dmenu-ee
[vertfull]: http://tools.suckless.org/dmenu/patches/vertfull
[scrolloff]: https://github.com/toolpunk/dmenu-ee/issues/3

Requirements
------------

In order to build ddmenu you need the Xlib header files.

Installation
------------
Edit config.mk to match your local setup (ddmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install ddmenu
(if necessary as root):

    make clean install

Running ddmenu
-------------

See the man page for details. The command is still `dmenu`.
