# KVM-Opencore

This is a fork of [Leoyzen's OpenCore image](https://github.com/leoyzen/KVM-Opencore) for QEMU/KVM, 
which I've extended to add a build system for automatically buliding all of the required files from 
sourcecode, and to keep up with the latest OpenCore changes.

It is currently tested to boot macOS Catalina, Big Sur, and Monterey, but will likely also boot older 
versions of macOS.

Although the images offered here should work on all QEMU/KVM distributions, I specifically build
and test these for my Proxmox Hackintosh guide here:

https://www.nicksherlock.com/2021/10/installing-macos-12-monterey-on-proxmox-7/

Note that although the images in the Releases have filenames like OpenCore-v15.iso, these aren't 
real ISOs, but rather raw hard disk images, and need to be booted as such. (They're just using .iso
extensions so they'll appear in Proxmox's disk image picker).
