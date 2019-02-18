
Debian
====================
This directory contains files used to package alpinebotd/alpinebot-qt
for Debian-based Linux systems. If you compile alpinebotd/alpinebot-qt yourself, there are some useful files here.

## alpinebot: URI support ##


alpinebot-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alpinebot-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alpinebotqt binary to `/usr/bin`
and the `../../share/pixmaps/alpinebot128.png` to `/usr/share/pixmaps`

alpinebot-qt.protocol (KDE)

