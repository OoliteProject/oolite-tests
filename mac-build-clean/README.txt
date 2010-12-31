build-clean.sh

This script will check out a clean copy of Oolite trunk, and build five copies
of it:
* Debug-ppc
* Debug-i386
* Debug-x86_64
* TestRelease (universal)
* Deployment (universal)

The working copy is made in a directory called "clean" within the current
working directory, which will be deleted first if it already exists. Build
results are written to text files inside the working directory.

As you may imagine, this is slow. On my 2007 iMac, it takes about 40 minutes.
If you show off about it being much faster on your machine, I'll force you to
do it nightly.

If you plan on running this, I suggest excluding the enclosing directory from
Time Machine backups.
