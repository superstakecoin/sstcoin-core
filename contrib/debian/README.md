
Debian
====================
This directory contains files used to package sstcoin/sstcoin-qt
for Debian-based Linux systems. If you compile sstcoind/sstcoin-qt yourself, there are some useful files here.

## sstcoin: URI support ##


sstcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sstcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sstcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/sstcoin128.png` to `/usr/share/pixmaps`

sstcoin-qt.protocol (KDE)

