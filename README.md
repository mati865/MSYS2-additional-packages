MSYS2-additional-packages
==============

WARNING: This repository is not official. Official repository can be found here: https://github.com/Alexpux/MSYS2-packages

Additional package scripts for MSYS2.

To build these, run msys2_shell.bat then from the bash prompt.

    cd ${package-name}
    makepkg

To install the built package(s).

    pacman -U ${package-name}*.pkg.tar.xz

If you don't have the group base-devel installed, please install.

    pacman -S base-devel
