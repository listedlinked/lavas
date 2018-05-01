
Debian
====================
This directory contains files used to package lavasd/lavas-qt
for Debian-based Linux systems. If you compile lavasd/lavas-qt yourself, there are some useful files here.

## lavas: URI support ##


lavas-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lavas-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lavasqt binary to `/usr/bin`
and the `../../share/pixmaps/lavas128.png` to `/usr/share/pixmaps`

lavas-qt.protocol (KDE)

