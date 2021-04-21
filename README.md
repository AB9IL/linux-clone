# linux-clone
Clone a Linux filesystem and install grub bootloader to any partition you select.

### What it does:
The clone script uses rsync to clone an operating linux filesystem to any selected partition.

### Format the target partition first, and bake it bootable.
   It is your choice to use ext4, ext3, btrfs, or whatever...

### Dependencies
fzf rsync grub2
