# Lenovo V330-14IKB 14" | Intel i5 (8250U)

[![macOS](https://img.shields.io/badge/macOS-11.4-orange)](https://www.apple.com/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.0-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-last%20version-blue.svg)](https://github.com/sutsurup/Lenovo-V330-Hackintosh/releases)

<img align="right" src="Images/Lenovo-V330.png" alt="Lenovo" height="260" width="363">

[Türkçe](README.md) | English

**macOS Version: 11.4**

**OpenCore Version: 0.7.0**

Helpful resources:

- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide)

# Details

    Date:         May 21, 2021
    Status:       Stable
    Support:      BIOS (429.100.7.0.0)
    Build:        OpenCore

## Hardware

| **LENOVO** | Detail                                                 |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo V330-14IKB      |
| Motherboard           | 	Lenovo V330     |
| CPU              | Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz KabyLake R              |
| RAM           | 2400 MHz onBoard 4 GB + BigBoy 8GB DDR4 2666 MHz SODIMM (Total: 12GB)   |
| Integrated Graphics | Intel(R) UHD Graphics 620 (1 GB)                    |
| Wi-Fi | Intel(R) Dual Band Wireless-AC 3165                |
| Audio       | Conexant CX20751/2 (Layout: 3)                        |
| BIOS Version      | 429.100.7.0.0                   |

![](Screenshots/info.png)

## Compatibility
It runs stably on **macOS Big Sur 11.4**. You can update to version 11.4 and below.
Since version 11.4 could not be installed directly, a clean installation of 10.15.7 (Catalina) was first performed with original Apple files, and then it was updated to 11.4 (Big Sur).
I have shared a zip file for the EFI folder in the Releases section. Create a folder named EFI in the EFI partition of your macOS installation media and copy the BOOT and OC folders from the zip file into the EFI folder.
You can try running it on macOS High Sierra 10.13.6, Mojave 10.14.6, Catalina 10.15.7, and Big Sur 11.4.

### Working Hardware

- [x] Sleep Mode
- [x] Ethernet (Patched)
- [x] Wi-Fi + Bluetooth (openIntelWireless, without HeliPort)
- [x] Audio and Microphone (Layout: 3)
- [x] Battery percentage indicator

### Non-Working Hardware
- [ ] Screen brightness
- [ ] HDMI (Not fully functional)

![](Screenshots/update.png)

## Useful Post-Installation Guides
* **Recommended:** If you want to use iCloud, iMessage, or FaceTime, follow this guide strictly: [Enabling iMessage and Apple Services with OpenCore](https://osxinfo.net/konu/opencore-ile-imessage-ve-apple-servislerini-aktif-etmek.16297/) (Although this guide shows Clover Configurator, you can follow the steps using OpenCore Configurator.)
* [ProperTree](https://osxinfo.net/konu/propertree-opencore-bootloader-icin-config-duzenleyici.12919/) (for editing config.plist)
* Hackintool ([Forum Thread](https://www.insanelymac.com/forum/topic/335018-hackintool-v286/) | [Direct Download](http://headsoft.com.au/download/mac/Hackintool.zip)) (For detailed system information and adjustments)

## Contact
If you encounter any issues, you can primarily get support through the [GitHub Issues](https://github.com/sutsurup/Lenovo-V330-Hackintosh/issues) page.
For other questions, you can use the following channels:

- **Website:** [sutsurup.tr](http://sutsurup.tr)
- **Mail:** [veysel@sutsurup.tr](mailto:veysel@sutsurup.tr)

## Screenshots
![](Screenshots/BigSur.png)

</details>

## Support
If you find the project useful, you can donate to help me find resources:
```
₿ 1Q8CEMHTuecxPUJpEdpRiG6Bg2GVtzw4bN
```
<a href='https://github.com/sutsurup/sutsurup/blob/main/Donate.md'><img alt='Donate' src='https://github.com/sutsurup/MSI-Hackintosh-Build/blob/main/Images/donate.png?raw=true' height='360px' width='375px'/></a>
```
Click on the QR code to access alternative donation options.
```
