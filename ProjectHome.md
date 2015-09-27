# phelper #

## What is phelper? ##

The name _phelper_ comes from _preseed helper_.

You can find more about what a _preseed_ is in the following links:

  * http://d-i.alioth.debian.org/manual/en.i386/apb.html
  * http://wiki.debian.org/DebianInstaller/Preseed

## What can phelper do? ##

Note: At now phelper is under development, and I only have some sh scripts and functions, that make the work (as you can [see](http://inigo.homeunix.net/sites/default/files/phelper0.1.png)). I have open this google-code hosted site, for a complete rewrite, probably using perl or python.

phelper is a program for generating and managing preseed configurations, organized in profiles. Each profile will be editable, and customized with different tasks to be launched via late\_command on the debian installer.

It should work from command line, to graphical Desktops and may be also a web version.

The default, and the saved profiles, should be released to different targets:

  * disk
  * ftp
  * sftp
  * scp
  * custom iso, with the preseed and related files included.
  * other d-i formats, with the preseed and related files included.