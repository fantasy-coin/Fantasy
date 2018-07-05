
Debian
====================
This directory contains files used to package fantasyd/fantasy-qt
for Debian-based Linux systems. If you compile fantasyd/fantasy-qt yourself, there are some useful files here.

## fantasy: URI support ##


fantasy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fantasy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fantasyqt binary to `/usr/bin`
and the `../../share/pixmaps/fantasy128.png` to `/usr/share/pixmaps`

fantasy-qt.protocol (KDE)

