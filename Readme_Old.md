# This is the old readme as a new one might be replacing the default one within a few days. 

# Xubuntu-9.04-Wii

This version is no longer maintained by me or ubuntu devs. Please upgrade to Ubuntu 14. https://github.com/Wiibuntu/Ubuntu14-Wii

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

# V1.2 Coming Soon! - Will boot via gumboot like the rest of my ubuntu versions and the kernel SHOULD be more stable. (Note: You will loose any data you had on ubuntu 9, so back it up!)

# TRY UBUNTU 16!
Ubuntu 16 is in its EARLY STAGES and I have decided to open those early stages up to everyone! Please give  it a try [here](https://github.com/Wiibuntu/Ubuntu-16.04-Wii)
