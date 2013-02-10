bob.arch
========

Arch linux specific files for bob.

Each directory contains a PKGBUILD file.  To build, cd to that
directory and type

 makepkg

Right now, the bob package is actually bob-git; that is, it will build
bob from git rather than download a specific versioned distribution.
As it stabalises it may make sense to add a package based build.

Notes
-----

libsvm https://aur.archlinux.org/packages/libsvm/ was updated by the
maintainer on request (header file, .so link).

blitz https://aur.archlinux.org/packages/blitz/ has a pending request
to remove the pkgconfig line.
