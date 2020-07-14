# Hackintosh with HP Spectre x360 13

OpenCore configuration files, installation guides and resources to run macOS on the HP Spectre 13-4101dx (may work with similar devices, but there is no guarantee).

**Disclaimer:** This project is still in alpha/beta stage. Proceed at your own risk, and feel free to report issues and contribute to this guide :)

### Folder structure

- `ACPI` contains original, disassembled & patched DSDT/SSDT files, and a small patching guide.
- `Install` contains the EFI files & installation guides for different versions of macOS.
- `Utilites` contains a pre-built version of HeliPort to manage your WiFi networks.

### Supported macOS versions

- macOS Catalina (tested with 10.15.5 & 10.15.6, [instalation notes...](Install/Catalina/))
- macOS Big Sur (WIP, [instalation notes...](Install/BigSur/))

**Note:** I got the computer to boot and work decently with Big Sur. However, the Big Sur project is on pause until the OS is more widely tested, I ran into many issues regarding the OS itself (rather than my Hackintosh config), any effort as of now could be invalidated in the near future with a substantial bug fix/update. For the momnent, I'll continue working on improving Catalina support.

### ACPI patching

This computer requires you to load a patched DSDT on your OC installation to get the battery & trackpad to work. For more information, check the [ACPI](ACPI/) folder.

### Credits

- [Apple](https://www.apple.com) for macOS  
- [Acidanthera authors](https://github.com/acidanthera) for providing OpenCore, VirtualSMC, Lilu, WhateverGreen, AppleALC & VoodooPS2
- [OpenIntelWireless authors](https://github.com/OpenIntelWireless) for providing support for Intel WiFi cards to macOS

