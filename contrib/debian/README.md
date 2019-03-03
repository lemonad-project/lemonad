
Debian
====================
This directory contains files used to package lemonadd/lemonad-qt
for Debian-based Linux systems. If you compile lemonadd/lemonad-qt yourself, there are some useful files here.

## lemonad: URI support ##


lemonad-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lemonad-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lemonadqt binary to `/usr/bin`
and the `../../share/pixmaps/lemonad128.png` to `/usr/share/pixmaps`

lemonad-qt.protocol (KDE)

