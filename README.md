# Asus_v5000j_Opencore_EFI
Opencore's EFI for Asus v5000j and some utilities

How to unlock cfg for Asus v5000j:
1. Create a bootable usb containing ru.efi
- Download `ru.efi` [here](http://ruexe.blogspot.com/)
- Rename `ru.efi` to `BOOTX64.efi`
- Grab a usb and format it to FAT32
- Create a `EFI` folder
- Create a `BOOT` folder
- Paste the `BOOTX64.efi` here
2. Boot the usb (you may want to use BIOS to boot it)
3. Now we are going to turn off cfg lock
- Press `ENTER`
- Press `ALT` + `=`
- Use up and down button and navigate to `Cpusetup`, press `ENTER`
- Use up and down and left and right button to navigate to `0043`(which means that the upper-left number should say `0043`)
- Press `ENTER`, press `0`, press `ENTER`
- Press `CTRL` + `w`
- Press `ENTER`
- Power off your machine
