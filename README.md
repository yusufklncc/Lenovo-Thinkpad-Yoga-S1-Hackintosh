<!-- omit in toc -->
#  macOS on Lenovo Thinkpad Yoga S1

<h3> 
    English
</h3>

<img align="right" src="https://i.loli.net/2021/02/18/yip3eNsQWUZlFkd.png" width="400px" alt="preview">

OpenCore config for Hackintosh OpenCore Lenovo Thinkpad Yoga S1.

[![macOS](https://img.shields.io/badge/macOS-11.6.1-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.4-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/Lenovo-Yoga-S1-Hackintosh/releases)

## Screenshot
<details>
<summary>Big Sur & Mojave</summary>

![](https://github.com/relaxewdy/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/BigSur.png)
![](https://github.com/relaxewdy/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/Mojave.png)

</details>

<!-- omit in toc -->
# Laptop's Hardware

| **LENOVO** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo Thinkpad Yoga S1      |
| CPU              | Intel(R) Core(TM) i7-4510U CPU @ 2.0GHz (max 3.10Ghz) Haswell             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Internal Graphics Card | Intel® HD Graphics 4400                     |
| Wi-Fi             | Intel Wireless 7260 |
| Sound       | Conexant CX20751                       |

# Update History
- [x] macOS Big Sur 11.6.1
- [x] macOS Big Sur 11.5.2
- [x] macOS Big Sur 11.0.1

# What's Working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel HD Graphics 4400              |  ✅  |
|  Brightness control                  |  ✅  |
|  Audio Conexant CX20751 (id:28)      |  ✅  |
|  3.5mm Combojack                     |  ✅  |
|  Intel 7260 Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅  |
|  USB 3.0 (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Touchscreen with gestures           |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  Shutdown / Reboot   |  ✅  |
|  Fn shortcut keys   |  ✅  | 
|  S3 Sleep / Wake   |  ✅  |

# What's not working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Airdrop, Sidecar (Beacuse Intel Wi-Fi)   | ❌ |

# What You Have to Do?
|                                 |                                    |
| -----------------------------------  | -------- |
|  SMBIOS Settings  | ⚠️ |
 
With OpenCore Configurator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 11,1
