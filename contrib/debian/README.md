
Debian
====================
This directory contains files used to package wildnoded/wildnode-qt
for Debian-based Linux systems. If you compile wildnoded/wildnode-qt yourself, there are some useful files here.

## wildnode: URI support ##


wildnode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wildnode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wildnodeqt binary to `/usr/bin`
and the `../../share/pixmaps/wildnode128.png` to `/usr/share/pixmaps`

wildnode-qt.protocol (KDE)

