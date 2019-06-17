
Debian
====================
This directory contains files used to package ghrcoind/ghrcoin-qt
for Debian-based Linux systems. If you compile ghrcoind/ghrcoin-qt yourself, there are some useful files here.

## ghrcoin: URI support ##


ghrcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ghrcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ghrcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ghrcoin128.png` to `/usr/share/pixmaps`

ghrcoin-qt.protocol (KDE)

