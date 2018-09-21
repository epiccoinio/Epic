
Debian
====================
This directory contains files used to package epicd/epic-qt
for Debian-based Linux systems. If you compile epicd/epic-qt yourself, there are some useful files here.

## epic: URI support ##


epic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install epic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your epicqt binary to `/usr/bin`
and the `../../share/pixmaps/epic128.png` to `/usr/share/pixmaps`

epic-qt.protocol (KDE)

