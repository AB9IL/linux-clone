# linux-clone
Clone a Linux filesystem and install grub bootloader to any partition you select.


### What it does:
The clone script uses rsync to clone an operating linux filesystem to any selected partition.


### Format the target partition first, and bake it bootable.
It is your choice to use ext4, ext3, btrfs, or whatever...
This script does not format any partitions.


### Dependencies
fzf rsync grub2


### Usage
```bash
linux-clone
```


### Warning!
Make sure that you select the correct partition!  This script will write to whichever one you select.
