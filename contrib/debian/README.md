
Debian
====================
This directory contains files used to package bitcrore_coind/bitcrore_coin-qt
for Debian-based Linux systems. If you compile bitcrore_coind/bitcrore_coin-qt yourself, there are some useful files here.

## bitcrore_coin: URI support ##


bitcrore_coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcrore_coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcrore_coin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcrore_coin128.png` to `/usr/share/pixmaps`

bitcrore_coin-qt.protocol (KDE)

