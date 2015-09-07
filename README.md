Arelos Iso building script.
=========================

This is the bash script for generating iso images for Arelos.

It is a bash script, similar to Remastersys and its forks.  The script is 
based on the Distroshare Ubuntu Imager. https://www.distroshare.com

To run the script, run it from the directory where it is located.  For example:

To boot the ISO from a USB stick, you can use the dd command like this:

dd if=isoimage.iso of=/dev/sdb bs=1M

where sdb is your USB drive.  You should be able something similar on Mac OS X.
You can also use UNetbootin: http://unetbootin.sourceforge.net/ to create a 
bootable USB drive.

Ubuntu Startup Disk creator won't be able to turn the iso into a bootable 
usb drive since the Arelos Iso script uses grub2 as the bootloader.
