# Note

Doc: https://www.freebsd.org/doc/en_US.ISO8859-1/books/developers-handbook/index.html

Also chekcout TrueOS: https://github.com/trueos/trueos

[Layout](https://www.freebsd.org/doc/en_US.ISO8859-1/books/developers-handbook/introduction-layout.html)
```
Directory	Description
bin/	Source for files in /bin
cddl/	Utilities covered by the Common Development and Distribution License
contrib/	Source for files from contributed software.
crypto/	Cryptographical sources
etc/	Source for files in /etc
gnu/	Utilities covered by the GNU Public License
include/	Source for files in /usr/include
kerberos5/	Source for Kerberos version 5
lib/	Source for files in /usr/lib
libexec/	Source for files in /usr/libexec
release/	Files required to produce a FreeBSD release
rescue/	Build system for the /rescue utilities
sbin/	Source for files in /sbin
secure/	Contributed cryptographic sources
share/	Source for files in /usr/share
sys/	Kernel source files
tests/	The FreeBSD test suite
tools/	Tools used for maintenance and testing of FreeBSD
usr.bin/	Source for files in /usr/bin
usr.sbin/	Source for files in /usr/sbin
```

This repo is really a monster, you can find everything here.
For all commands you've came across, it's likely you will find the source code here!

## Compiler

- usr.bin/clang

## Kernel

- sys/
- sys/vm
- sys/sys
