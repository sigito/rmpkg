rmpkg
=====

Utility for removing packages without Bom files in Receipts directory.

Usage:

```bash
rmpkg [-f] [-d] -p path-to-pkg
    -f – force delete files. Will not ask for deletion of every file.
    -p path-to-pkg – specify path to package to delete.
    -d – remove whole directory with package installation.
```
Removes package from Mac OS X system by it's installation archive.

For more: http://it-routings.blogspot.com/2013/02/remove-package-in-mac-os-x.html
