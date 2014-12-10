YUMI Fork
============

Fork of YUMI, the Multiboot USB Creator, in version "2.0.1.2".

This fork implement the feature, to use multiboot on local disk using the existing boot manager BCD of your Microsoft® Windows installation.

I wanted to test new LINUX distributions, but didn't always have a USB stick lying around to rip the ISO on it - and to burn a CD or DVD would be just a waste. So why not bypass the USB stick and just coping the ISO contents to Windows C: drive, add a boot entry to the windows boot-manager and just boot? Well, with this tool you can :)


**There is no release yet!**


Installation
-
Start the setup file.


Build
-
# Install NSIS (Nullsoft Scriptable Install System) from http://nsis.sourceforge.net/Download.
# Open NSIS from the start menu.
# Goto "Compile NSI scripts".
# Open File "YUMI.nsi". Compilation starts.
# YUMI "YUMI-2.0.1.2.exe" was created in the same directory.


FAQ
-
Why is this code not merged into YUMI
 It will be maybe once. But this YUMI fork also has an uninstaller. YUMI doesn't have this uninstaller cause it doesn't install on locally but on a removable device.
 
 
TODO
-
1. Make an Ubuntu-only Installation from Scratch (like WUBI) - no option
 squashfs and all other required files included in EXE
2. Make an iPXE-only Installation from Scratch
 (possible to start it directly from BCD???)
3. Possible to check if there is syslinus already installed?
 Check for C:\multiboot



