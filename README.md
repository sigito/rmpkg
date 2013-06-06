rmpkg
=====

Utility for removing packages without Bom files in Receipts directory.

Usage:

```bash
rmpkg [-hfd] [-t tmp_dir] -p path-to-pkg
    -p path-to-pkg – specify path to package to delete.
    -h - print short description and this message.
    -f – force delete files. Will not ask for deletion of every file.
    -d – remove whole directory with package installation.
    -t tmp_dir - specify directory to put temporal files to. Default is /tmp.
```
Removes package from Mac OS X system by it's installation archive.

For more: http://it-routings.blogspot.com/2013/02/remove-package-in-mac-os-x.html
