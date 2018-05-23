
Debian
====================
This directory contains files used to package vetanid/vetani-qt
for Debian-based Linux systems. If you compile vetanid/vetani-qt yourself, there are some useful files here.

## vetani: URI support ##


vetani-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vetani-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vetaniqt binary to `/usr/bin`
and the `../../share/pixmaps/vetani128.png` to `/usr/share/pixmaps`

vetani-qt.protocol (KDE)

