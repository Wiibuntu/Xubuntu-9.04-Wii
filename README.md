# Xubuntu-9.04-Wii

This repository contains the rootfs of Xubuntu 9.04 for the Wii. The same rootfs you will be downloading.

# How to Install (Homebrew Needed!)
In the download section you will find a .img file. That file will contain two partitions: a fat32 partition and a ext3 partition. The fat32 partition will contain the Linux loader for the Homebrew Channel.

Just flash this image to an SD Card (8gb or more needed!)

# Ubuntu Login
The default username is "ubuntu"
The default password is "ubuntu"

# Start X Server
At first this xubuntu build used GDM which the Wii couldn't load, so I removed that and installed xfce4 which loads fine.
After you login, just type "startx" and the desktop will begin to load.

# Ethernet / WiFi
USB to Ethernet adapter works fine. To use WiFi you must boot into Ubuntu from BootMii, But that has not been tested.

# Packages / Updates
Ive already updated/upgraded the system, all of the repos are already also set to the old.releases repos.

# Swap
There is a 2GB swapfile that is in / that auto mounts at boot. Due to the Wii having such little RAM its needed to do anything.

## NOT TESTED ON vWii or Gamecube!

## No DVD Support YET.

# Built off
- http://forum.wiibrew.org/read.php?29,70776
