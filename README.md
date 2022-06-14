# macOS-Ventura-X99-Hackintosh (Gigabyte X99 Ultra Gaming, i7-6850K, RX5700XT)

[GUIDE] Install macOS-Ventura OpenCore Botloader UEFI

STEP 1: Download macOS Ventura

The full operating system is a free download for anyone who has a Mac.

Purchase a 16-32 GB  USB drive
Open Mac App Store
Log in with your Apple ID
Download macOS Ventura The Application Install macOS Ventura will appear in /Applications.
STEP 2: Create a Bootable USB Drive with terminal.

Insert the USB drive
Open /Applications/Utilities/Disk Utility
Left corner click / View / Show all devices
Highlight the USB drive in left column
Click Erase button
For Name: type USB (You can rename it later)
For Format: choose Mac OS Extended (Journaled) GUID
Click Erase then Done
Copy paste the falowing command in terminal; sudo /Applications/Install\ macOS\ Ventura.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --nointeraction && say Ventura Drive Created ( change (USB) with your erased usb name)
STEP 3 Replace your EFI folder with mine from; X99 i7-6850K _RX5700XT_OC_VENTURA_14.06.2022

STEP 4: Recommended BIOS Settings in general

If you're installing on a recommended CustoMac desktop with AMI UEFI BIOS, the options are simple. For other systems make sure to set your BIOS to Optimized Defaults, and your hard drive to AHCI mode.

To access BIOS/UEFI Setup, press and hold Delete on a USB Keyboard while the system is booting up
Load Optimized Defaults
If your CPU supports VT-d, disable it
If your system has CFG-Lock, disable it
If your system has Secure Boot Mode, disable it
Set OS Type to Other OS
If your system has IO Serial Port, disable it
Set XHCI Handoff to Enabled

Save and exit.

STEP 5: Install macOS Mojave

All you need to do is boot from the USB drive and install! Insert the USB in a USB 2.0 port.

Turn on the computer
Press the hotkey to choose boot device (F12 for Gigabyte motherboards, F8 for ASUS motherboards, F11 for ASrock motherboards)
Choose your USB
At Open Core boot screen, choose Boot OS X Install from Install macOS Ventura
When you arrive at the Installer, choose language.
For a new installation of macOS, you MUST erase and format the destination drive according to the following steps before continuing. • a. In the top menu bar choose Utilities, and open Disk Utility • b. Left corner click / View / Show all devices • c. Highlight your target drive for the Ventura installation in left column. • d. Click Erase button • e. For Name: type macOS Ventura (You can rename it later) • f. For Format: choose Mac OS Extended (Journaled) or APFS • g. Click Erase • h. Close Disk Utility
When the installer asks you where to install, choose macOS Ventura
Upon completion, the system will automatically restart.
Press the hotkey to choose boot device (F12 for Gigabyte motherboards, F8 for ASUS motherboards, F11 for ASrock motherboards)
Choose Install macOS Ventura USB
At the Boot Screen, choose macOS Ventura
Complete macOS installation. The system will automatically reboot 3 times. Alwais boot back from your usb

STEP 6: Post Installation

The installation is complete, but the drive isn't bootable yet. Boot from the USB again, this time choosing macOS Ventura.

Press the hotkey to choose boot device (F12 for Gigabyte motherboards, F8 for ASUS motherboards, F11 for ASrock motherboards)
Choose USB
At the Boot Screen, choose your new macOS Ventura installation.
Complete macOS Ventura setup
Replace your EFI folder from EFI with mine and reboot; X99 i7-6850K _RX5700XT_OC_VENTURA_14.06.2022
At the Boot Screen, choose your new macOS Ventura HDD.
Reboot
You are done.. installation is complete, you have a full functional X99 Hackintosh !
