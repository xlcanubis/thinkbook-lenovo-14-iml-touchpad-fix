# thinkbook-lenovo-14-iml-touchpad-fix
The only thing that seems to work and which fixes the thinkbook 14 iml touchpad is to install this kernel

# instructions
1. download the three files
2. run ```cat touchpad_fixa* > touchpad_fix.deb``` to assemble the tree files into 1
3. run ```dpkg -i touchpad_fix.deb``` to install the package, which installs the kernel and adds 5.9 to your grub
4. reboot, hit ESC or whichever key allows you to select your kernel and select the newly added 5.9

this worked for me, thanks to Kai - the author of this pkg that fixes the touchpad for me and many others
