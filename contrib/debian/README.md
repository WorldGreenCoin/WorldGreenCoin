
Debian
====================
This directory contains files used to package worldGreenCoind/worldGreenCoin-qt
for Debian-based Linux systems. If you compile worldGreenCoind/worldGreenCoin-qt yourself, there are some useful files here.

## worldGreenCoin: URI support ##


worldGreenCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install worldGreenCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your worldGreenCoinqt binary to `/usr/bin`
and the `../../share/pixmaps/worldGreenCoin128.png` to `/usr/share/pixmaps`

worldGreenCoin-qt.protocol (KDE)

