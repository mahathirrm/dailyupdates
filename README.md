**********
to permanently mount the file system
**/etc/fstab** (File Systems Table) is a configuration file that tells Linux which filesystems to mount automatically at boot and how to mount them.
***********
**pvdisplay** is an LVM (Logical Volume Manager) command that shows detailed information about Physical Volumes (PVs) on your system.
**************
ls -l /dev/ | grep "^b"
Breakdown

ls -l /dev/
Lists all device files in /dev in long format.

| (pipe)
Sends the output to the next command.

grep "^b"
Filters lines that start with b.
Why b?
In ls -l output, the first character indicates file type:

Character	Meaning
b	Block device
