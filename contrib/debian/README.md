
Debian
====================
This directory contains files used to package allsafed/allsafe-qt
for Debian-based Linux systems. If you compile allsafed/allsafe-qt yourself, there are some useful files here.

## allsafe: URI support ##


allsafe-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install allsafe-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your allsafeqt binary to `/usr/bin`
and the `../../share/pixmaps/allsafe128.png` to `/usr/share/pixmaps`

allsafe-qt.protocol (KDE)

