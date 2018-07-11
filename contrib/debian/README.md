
Debian
====================
This directory contains files used to package bettexd/bettex-qt
for Debian-based Linux systems. If you compile bettexd/bettex-qt yourself, there are some useful files here.

## bettex: URI support ##


bettex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bettex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bettexqt binary to `/usr/bin`
and the `../../share/pixmaps/bettex128.png` to `/usr/share/pixmaps`

bettex-qt.protocol (KDE)

