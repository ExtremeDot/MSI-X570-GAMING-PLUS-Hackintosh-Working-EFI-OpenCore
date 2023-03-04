MainBoard : MSI MPG X570 Gaming Plus 
CPU : AMD Ryzen 5950X 16Core CPU
RAM 32GB
Graphic XFX Radeon 5700
OpenCore 6.00

I just collected files and tuned to work

Tested on BigSure 11.7.2 using Bootable Installer Disk from MacOS

## How to change Icon of MacOS boot entrey in OpenCore Boot menu?

you need to add ".VolumeIcon.icns" into preboot partition/folder of your mac.

* a: Download OpenCanpoy compatible icon file , you can download from https://github.com/blackosx/OpenCanopyIcons
for example my icon file is located on desktop with Apple.icns name.


* b: open Terminal and run commands
```sh
sudo -i 
```
enter your password to run commands as root

* c: type "cp" then drag Apple.icns into terminal window , then type commands below

you must change USERNAME and UIID Number with your own.

UIID must be like this: 51F87655F-1587-4AE1-8971-07A197956217
USERNAME : your user name

```sh
cp /Users/USERNAME/Desktop/Apple.icns /System/Volumes/Preboot/UIID/.VolumeIcon.icns

```
then reboot ypur mac to see new icon.

