
Debian
====================
This directory contains files used to package dravitecoinsd/dravitecoins-qt
for Debian-based Linux systems. If you compile dravitecoinsd/dravitecoins-qt yourself, there are some useful files here.

## dravitecoins: URI support ##


dravitecoins-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dravitecoins-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dravitecoinsqt binary to `/usr/bin`
and the `../../share/pixmaps/dravitecoins128.png` to `/usr/share/pixmaps`

dravitecoins-qt.protocol (KDE)

