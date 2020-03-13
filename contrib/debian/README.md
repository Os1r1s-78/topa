
Debian
====================
This directory contains files used to package topachaind/topachain-qt
for Debian-based Linux systems. If you compile topachaind/topachain-qt yourself, there are some useful files here.

## topachain: URI support ##


topachain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install topachain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your topachainqt binary to `/usr/bin`
and the `../../share/pixmaps/topachain128.png` to `/usr/share/pixmaps`

topachain-qt.protocol (KDE)

