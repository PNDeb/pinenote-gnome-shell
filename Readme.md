
# building a debian package

	 git clone -b pinenote/trixie https://github.com/PNDeb/pinenote-gnome-shell.git
	 apt build-dep gnome-shell
	 cd pinenote-gnome-shell
	 origtargz -d
	 dpkg-buildpackage -us -uc
