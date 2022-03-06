bc64e 

[alex-free.github.io](https://alex-free.github.io)
==================================================

Boot Camp 64 Enabler
====================

Apple does not officially support running 64-bit versions of Windows on all Macs with 64-bit processors. No official Boot Camp installer for example will run on the Early 2009 [MacBook 5,2](https://everymac.com/systems/apple/macbook/specs/macbook-core-2-duo-2.0-white-13-early-2009-nvidia-specs.html) running Windows 7 64-bit.

Boot Camp 64 Enabler allows Macs with a mobile Nvidia chipset (i.e. it has a 9400M or other Nvidia 'M' GPU in it) that do not officially support 64-bit [64-bit Windows](https://support.apple.com/en-us/HT205016#tables)/[Boot Camp 4](https://support.apple.com/kb/dl1635?locale=en_US) to run Windows 7 64-bit like an officially supported Mac by using a modifed Boot Camp 4 and updated Nvidia drivers.

[Homepage](https://alex-free.github.io/boot-camp-64-enabler) | [GitHub](https://github.com/alex-free/boot-camp-64-enabler)

Table Of Contents
-----------------

*   [Downloads](#downloads)
*   [Usage](#usage)
*   [License](#license)

![](images/bc64e-1.png)

![](images/bc64e-2.png)

![](images/bc64e-3.png)

![](images/bc64e-4.png)

Downloads
---------

### Version 1.0 (3/2/2022)

[Boot Camp 64 Enabler v1.0](https://github.com/alex-free/boot-camp-64-enabler/releases/download/v1.0/bc64e_1.0.zip) _for Windows 7 64-bit_

Using git:

Install [Git-LFS](https://www.atlassian.com/git/tutorials/git-lfs#installing-git-lfs), and then you can:

    git clone https://github.com/alex-free/boot-camp-64-enabler

Usage
-----

### Install or Dual-Boot Windows 7 64-bit

Using an already installed Mac OS X installation or a Mac OS X installer, use `Disk Utility.app` to make a FAT 32 partition named `WIN7` or similar. Then, reboot your Mac with a Windows 7 64-bit DVD in your internal drive or an external USB one while pressing the `c` key. Install Windows 7, and boot to your new installation.

### Use Boot Camp 64 Enabler To Install Boot Camp And Nvidia Windows Drivers For Your Mac

[Download](#download) the latest release and extract it. In the extracted release directory is the `bc64e.bat` batch script file, just double click it to **run all the installers automatically and silently without any user interaction**.

When you first double click the `bc64e.bat` file it will prompt you for admin access automatically (needed to run the installers) since you won't have 2 finger tap to right click functionallity using the touch pad on your MacBook yet. So you wouldn't otherwise be able to right click and "`Run As Administrator`" since Boot Camp 64 Enabler has not yet been installed.

Your screen may temporarily go black and adjust the resolution for a few seconds while the drivers are being automatically installed. Once `bc64e.bat` completes and asks you to reboot your Mac, do so. You will reboot into a working system, which even includes the Boot Camp preferences no different then an officially supported Boot Camp 64-bit Mac!

License
-------

BootCamp 64 Enabler itself is released into the Public Domain, see the file `unlicense.txt` in each release of Boot Camp 64 Enabler. The included Boot Camp 4, the Nvidia drivers, and Dotnet are all under their own respective licenses.