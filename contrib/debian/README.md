
Debian
====================
This directory contains files used to package eschcoind/eschaton-qt
for Debian-based Linux systems. If you compile eschcoind/eschaton-qt yourself, there are some useful files here.

## eschaton: URI support ##


eschaton-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eschaton-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eschaton-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

eschaton-qt.protocol (KDE)

