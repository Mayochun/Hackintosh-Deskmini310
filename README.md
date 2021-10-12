# Hackintosh for Deskmini 310

+ OS : macOS Big Sur 11.6
+ Boot Loader : Open Core v0.7.4
+ UEFI Version : P4.40

![Hackintosh](https://user-images.githubusercontent.com/92324644/136828898-e7c55572-3407-457e-92ac-9343d83c8e62.jpg)

## Configuration

| Specifications | Detail                           |
|----------------|----------------------------------|
| Barebone Kits  | Asrock Deskmini 310              |
| CPU            | Intel Core i5 9400               |
| RAM            | DDR4 2400MHz 8Gx2 (16GB)         |
| WLAN           | Intel Dual Band Wireless-AC 3168 |
| SSD            | WD BLUE 3D NAND SATA SSD 500GB   |

## UEFI

Load UEFI Defaults

+ Advanced
    + CPU Configuration
        + CPU C States Support: Disabled
    + Chipset Configuration
        + Onboard HD Audio: Enabled
        + Onboard HDMI HD Audio: Enabled
        + VT-d: Disabled
    + Super IO Configuration
        + Serial Port: Disabled
    + USB Configuration
        + XHCI Hand-off: Enabled
+ Security
    + Secure Boot: Disabled
    + Intel Platform Trust Technology: Enabled
+ BOOT
    + CSM: Disabled

## Notes *Japanese

HackintoshでDeskmini 310にmacOS Big Surをインストールします。
macOSのインストーラーについては各自で入手してください。
Windows 11と一緒に使う場合はSecure Bootを使い分けてください。

Translation by Google Translate

Install MacOS Big Sur on Deskmini 310 with Hackintosh.
Please obtain your own for the MacOS installer.
Please switch Secure Boot if used with Windows 11.

