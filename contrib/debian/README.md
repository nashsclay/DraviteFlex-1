
Debian
====================
This directory contains files used to package draviteflexd/draviteflex-qt
for Debian-based Linux systems. If you compile draviteflexd/draviteflex-qt yourself, there are some useful files here.

## draviteflex: URI support ##


draviteflex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install draviteflex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your draviteflexqt binary to `/usr/bin`
and the `../../share/pixmaps/draviteflex128.png` to `/usr/share/pixmaps`

draviteflex-qt.protocol (KDE)

