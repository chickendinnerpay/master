
Debian
====================
This directory contains files used to package chickendinnerd/chickendinner-qt
for Debian-based Linux systems. If you compile chickendinnerd/chickendinner-qt yourself, there are some useful files here.

## chickendinner: URI support ##


chickendinner-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chickendinner-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chickendinner-qt binary to `/usr/bin`
and the `../../share/pixmaps/chickendinner128.png` to `/usr/share/pixmaps`

chickendinner-qt.protocol (KDE)

