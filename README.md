# Debian Project README
This is a shell for creating a Debian package to install BTT-Writer on Linux.

BTT-Writer will be installed in `/opt`

Be sure to edit `DEBIAN/control` file to update version number.

As root, run `dpkg-deb --build «deb file name»` from the root of this project.
