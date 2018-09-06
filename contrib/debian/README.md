
Debian
====================
This directory contains files used to package zenadd/zenad-qt
for Debian-based Linux systems. If you compile zenadd/zenad-qt yourself, there are some useful files here.

## zenad: URI support ##


zenad-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zenad-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zenadqt binary to `/usr/bin`
and the `../../share/pixmaps/zenad128.png` to `/usr/share/pixmaps`

zenad-qt.protocol (KDE)

