EFI ZIP configured! ( MacOS Sequoia 15.7 )

If you have a Dell 7580 notebook model, it may be possible to create a Hackintosh using the following EFI contained in this repository. Remember to format your USB drive to FAT32.

What's Working ?

Bluetooth
Keybord / keybord usb isn't working led
trackpad ( in the settings )
sleep mode, restart
last update sequoia 15.7
3 USB Ports 2.0 and 3.0
Battery it's normal
location services, siri, NOT working iServices on device
Display Light 
Audio ( the value is 23 )

the process are aptimized and working 95% without problems, so you can use the Heliport 
to Wifi. KEXT is on folder EFI.

Don't upgrade your hackintosh to MacOS Tahoe 26, just update the system! 
install homebrew!!

*/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)*

Attention: You need to use a wired internet connection to install the system on your SSD, as it depends on your network being compatible with HELIPORT, which you can find on GitHub here after installation on your SSD.

link HeliPort: https://github.com/OpenIntelWireless/HeliPort
install and reboot your machine! it's working perfectly!

BR-ABNT2 NOT working! 
CRTL + V and CRTL + C NOT Working (Or maybe I was just too lazy to set it up! )

If the folder doesn't appear in LOCATION in Finder, locate your disk and mount the EFI (usually located in sdks2). After mounting, move the EFI only from the USB drive to the EFI created by OCAT, unmount it, restart the system, go to the BIOS, look for bootx64 and set it as the priority. You can access the BIOS with F12. After that, remember to change the audio value in OCAT to 23 in DP. Choose the second option and change the value! Save and restart.
You can use your USB with ANDROID and tethering bluetooth to wifi usb tethering.

Use OCAT and create a ESP and move the EFi in your Pendrive USB to EFI SSD and unmount and reboot your system!

link OCAT: *https://github.com/ic005k/OCAuxiliaryTools/releases/tag/20250001*
