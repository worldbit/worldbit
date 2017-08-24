
Debian
====================
This directory contains files used to package worldbitd/worldbit-qt
for Debian-based Linux systems. If you compile worldbitd/worldbit-qt yourself, there are some useful files here.

## worldbit: URI support ##


worldbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install worldbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your worldbit-qt binary to `/usr/bin`
and the `../../share/pixmaps/worldbit128.png` to `/usr/share/pixmaps`

worldbit-qt.protocol (KDE)

