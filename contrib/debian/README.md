
Debian
====================
This directory contains files used to package cellscoind/cellscoin-qt
for Debian-based Linux systems. If you compile cellscoind/cellscoin-qt yourself, there are some useful files here.

## cellscoin: URI support ##


cellscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cellscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cellscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/cellscoin128.png` to `/usr/share/pixmaps`

cellscoin-qt.protocol (KDE)

