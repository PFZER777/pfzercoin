
Debian
====================
This directory contains files used to package pfzercoind/pfzercoin-qt
for Debian-based Linux systems. If you compile pfzercoind/pfzercoin-qt yourself, there are some useful files here.

## pfzercoin: URI support ##


pfzercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pfzercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pfzercoinqt binary to `/usr/bin`
and the `../../share/pixmaps/pfzercoin128.png` to `/usr/share/pixmaps`

pfzercoin-qt.protocol (KDE)

