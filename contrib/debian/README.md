
Debian
====================
This directory contains files used to package lykosd/lykos-qt
for Debian-based Linux systems. If you compile lykosd/lykos-qt yourself, there are some useful files here.

## lykos: URI support ##


lykos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lykos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lykosqt binary to `/usr/bin`
and the `../../share/pixmaps/lykos128.png` to `/usr/share/pixmaps`

lykos-qt.protocol (KDE)

