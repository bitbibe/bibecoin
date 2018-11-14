
Debian
====================
This directory contains files used to package bibecoind/bibecoin-qt
for Debian-based Linux systems. If you compile bibecoind/bibecoin-qt yourself, there are some useful files here.

## bibecoin: URI support ##


bibecoin-qt.desktop  (Gnome / Open Desktop)
To install:

        sudo desktop-file-install bibecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bibecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bibecoin128.png` to `/usr/share/pixmaps`

bibecoin-qt.protocol (KDE)

