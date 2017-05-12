
Debian
====================
This directory contains files used to package sosd/sos-qt
for Debian-based Linux systems. If you compile sosd/sos-qt yourself, there are some useful files here.

## sos: URI support ##


sos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sos-qt binary to `/usr/bin`
and the `../../share/pixmaps/sos128.png` to `/usr/share/pixmaps`

sos-qt.protocol (KDE)

