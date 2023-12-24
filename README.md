# Hackintosh for Deskmini 310

+ OS : macOS Ventura 13.6.3
+ Boot Loader : Open Core v0.9.7
+ UEFI Version : P4.40

![Skin](misc/Hackintosh.png)

## Configuration

| Specifications | Detail                           |
|----------------|----------------------------------|
| Barebone Kits  | Asrock Deskmini 310              |
| CPU            | Intel Core i5 9400               |
| RAM            | DDR4 2400MHz 8Gx2 (16GB)         |
| WLAN           | Intel Dual Band Wireless-AC 3168 |
| SSD (Mac)      | WD BLUE 3D NAND SATA SSD 500GB   |
| SSD2 (Windows) | WD BLUE 3D NAND NVMe SSD 500GB   |

## UEFI

Load UEFI Defaults

+ Advanced
    + USB Configuration
        + XHCI Hand-off: Enabled
+ Security
    + Secure Boot: Disabled
    + Intel Platform Trust Technology: Enabled
+ BOOT
    + CSM: Disabled

## Notes *Japanese

HackintoshでDeskmini 310にmacOS Venturaをインストールします。
SMBIOSについては各自で生成する必要があります。Windows11と切り替えて使う場合は、Secure BootとIntel TPPをUEFIで切り替えてください。

Translation by Google Translate

Install MacOS Ventura on Deskmini 310 with Hackintosh.
For SMBIOS, you will need to generate your own; if you want to switch to Windows 11, please switch between Secure Boot and Intel TPP in the UEFI.

