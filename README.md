# My Album releases

Packages of **My Album**, the photo mosaic application for large screens. This repository holds only what an
installed My Album needs to update itself from its About dialog:

- `MyAlbum-<version>-windows-amd64.zip`: the Windows package of each version;
- `SHA256SUMS.txt`: the SHA-256 checksums of the packages (My Album checks the download against it);
- `changes.json`: the changes of the version (the issues it completes), which About shows under "What's new".

The source code is not here. Each GitHub Release is published by the build of the version; nothing is pushed by
hand. Versions marked "Pre-release" are test builds before release 1.0.

To install My Album on a computer without internet, see the installation guide that comes with the package.
