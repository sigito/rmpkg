rmpkg
=====

Utility for removing packages without Bom files in Receipts directory.

Usage:

```bash
rmpkg [-v] [-h] [-f] [-t tmp-dir] package-to-remove
	Removes package specified by package-to-remove.

	-v	Verbose mode. Will only go through package and print general information.
	-h	Print short description and this message.
	-f	Force delete files. Will not ask for delection of every file.
	-t tmp-dir
		Specify directory to put temporal files to. Default is /tmp.
```
Removes package from Mac OS X system by it's installation archive.

Note
-----
Software might damage data on your computer, use at your own risk.

For more: http://it-routings.blogspot.com/2013/02/remove-package-in-mac-os-x.html
