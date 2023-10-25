# Xubuntu-9.04-Wii

![alt text](https://github.com/Wiibuntu/Xubuntu-9.04-Wii/blob/main/photos/Wiibuntu.png?raw=true)

This repository contains images of Xubuntu 9.04 for the Wii. Downloads are found to your right (on desktop).

# How to Install (Homebrew Needed!)
In the download section you will find a .img.gz file. That file will contain a .img file with two partitions: a fat32 partition and a ext3 partition. The fat32 partition will contain the Linux loader for the Homebrew Channel.

Just flash this image to an SD Card (8gb or more needed!)
# *NOT TESTED ON USB BUT SHOULD WORK*

# Ubuntu Login
The default username is "ubuntu"
The default password is "Wiibuntu9"

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

## KNOWN ISSUES
-Some keyboard layouts dont work properly

-Issues connecting to some routers.

# Built off
- http://forum.wiibrew.org/read.php?29,70776
- https://gbatemp.net/threads/wii-linux-xwhiite-0-2-with-wi-fi-in-2020-tutorial.570945/
