# EFI OpenCore Folder for AMD FX or A-SERIES
 
## FOR SETUP GUIDE, PLEASE GO TO THE [WIKI](https://github.com/tditheo/EFIOC-AMD-FX-ASERIES/wiki)

## My Specifications
 
|  **Component**   | **Model**                                       |
| ---------------- | ------------------------------------------      |
| Processor        | AMD A8-7600 @ 3.1GHz (3.8Ghz Turbo)             |
| Motherboard      | Gigabyte GA-F2A88XM-HD3 (rev. 3.2/3.3) (BIOS FC)|
| RAM              | 8GB (2 x 4GB)                                   |
| GPU              | Sapphire ATI Radeon HD 5770                     |
| Audio Chipset    | ALC-887                                         |
| Ethernet         | Realtek RTL8111                                 |

**macOS version**: 11.0.1 \
**OpenCore version**: 0.9.2

### What's working :

- Ethernet
- GPU acceleration
- iMessage, FaceTime and others Apple Services

### What's not working :

- Audio (mic and sound) (due to AppleALC and AMD CPU)
- WiFi, Bluetooth, AirDrop, SideCar etc.. (because I don't have WiFi card)
- Some USB Ports (trying to map usb multiple times)

## Credits

- [Apple](https://apple.com) for macOS
- [AMD-OSX Developers](https://github.com/AMD-OSX) for kernel patches for AMD CPUs
- [Acidanthera](https://github.com/acidanthera) for OpenCore and most of used kexts
- [Trulyspinach](https://github.com/trulyspinach) for SMCAMDProcessor
- [Mieze](https://github.com/Mieze) for RealtekRTL8111 kext
- [DhinakG](https://github.com/USBToolBox) for USBToolBox
- [XLNC](https://github.com/naveenkrdy) for AppleMCEReporterDisabler kext
- [Dortania](https://github.com/dortania) for OpenCore configuration guides