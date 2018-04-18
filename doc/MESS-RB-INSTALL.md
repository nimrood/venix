# Installing Venix 86R 2.0 in MESS

This documents how to install Venix 86R in MESS running the Rainbow
emulation. You're on your own to get mame/mess, as well as translating
the keys to your variant.

## TL;DR Version

1. Install the hard drive / create the virtual hard drive
1. Low level format and partition the drive with wutil
1. Boot the Venix Boston Software Works extraction disk (vbswx1.img)
1. Partition the drive (again) as guided
1. Feed the floppys
1. Reboot (I forget, do I need to redo the bootable stuff with wutil here?)
1. Profit! You have a Venix 86R 2.0 BSW Edition system (the root password is gnomes).

## Original Documentaiton

The file VENIX_Install.pdf has the original instructions, scanned in
all their glory.  They are thin on the 'partition it' part, but
otherwise contain a good overview of the process. If you are
installing BSW, and you really want to install that unless you want to
be limited to the 10MB RD51 that's the only supported vanilla Venix
drive, then there will be additional prompts at the end for the 4 BSW
disks with the enhance UUCP, kermit, improved venix kernel, and bug
fixes to libc and the compiler.

## The Long, Plodding (but complete) Version

TBD, alas