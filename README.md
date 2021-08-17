<!-- omit in toc -->
#  macOS on Lenovo Thinkpad Yoga S1

<h3> 
    English |
    <a href="https://github.com/relaxewdy/Lenovo-Yoga-S1-Hackintosh/blob/main/README-tr.md">Türkçe</a>
</h3>

<img align="right" src="https://i.loli.net/2021/02/18/yip3eNsQWUZlFkd.png" width="400px" alt="preview">

OpenCore config for Hackintosh OpenCore Lenovo Thinkpad Yoga S1.

[![macOS](https://img.shields.io/badge/macOS-11.2-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.6-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/Lenovo-Yoga-S1-Hackintosh/releases)

## Screenshot
<details>
<summary>Big Sur</summary>

![](https://i.loli.net/2021/02/18/Kpv5x1JmXozOnPU.png)
    
<details>
<summary>Mojave</summary>

![](https://i.loli.net/2021/02/18/Kpv5x1JmXozOnPU.png)


</details>

<!-- omit in toc -->
## Hardware

| **Lenovo** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo Thinkpad Yoga S1      |
| CPU              | Intel(R) Core(TM) i7-4510U CPU @ 2.0GHz (max 3.10Ghz) Haswell             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Graphic Card | Intel® HD Graphics 4400                     |
| Wi-Fi             | Intel Wireless 7260 |
| Sound       | Conexant CX20751                       |

## BİOS Settings

- ### Bios Version: GQET63WW (1.43)
- ### Config
  - USB
    - USB UEFI BIOS Support = Enabled
    - Always On USB = Enabled
    - Always On USB - Charge in Battery = Disabled
    - USB 3.0 Mode  = Auto
  - Power
    - Intel SpeedStep Technology = Enabled
    - CPU Power Management = Enabled
  - CPU
    - Intel Hyper-Threading Technology = Enabled
  - Intel Smart Connect 
    - Disabled
- ### Security
  - Password
    - All Disabled
  - Security Chip
    - All Disabled
  - I/O Port Access
    - All Enabled
  - Secure Boot 
    - All Disabled 
- ### Startup
  - UEFI/Legacy Boot = UEFI Only
    - CSM Support = Yes
  - Boot Mode = Quick

İf i didn't write don't change anything.

## What are working

- Turbo boost and CPU frequency stage.
- Intel® HD Graphics 4400
  - Brightness control
- Audio Conexant CX20751 
  - layout-id: `28`
  - 3.5mm Combojack
- Intel Wireless 7260 Wi-Fi and Bluetooth (Handoff is working)
- USB Ports (Port Mapping)
- Touchpad (14 gestures are working)
- Touchscreen with gestures
- Battery status
- Camera
- Fn shortcut keys

## What aren't working

- Sleep / Wake
- Airdrop 
 
With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information.
  - MacBook Pro 11,1
