<h1 align="center"> macOS on Lenovo Thinkpad Yoga S1 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/macOS%20Lenovo%20Thinkpad%20Yoga%20S1.png" width="700">

<h4 align="center"> OpenCore config for Hackintosh Lenovo Thinkpad Yoga S1 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Ventura-orange" width="165"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.9.1-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh" width="145"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=white" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-white?logo=PayPal" width="140"/> </a>
<a href="https://www.buymeacoffee.com/yusufklncc">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" width="150"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#screenshot-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#whats-not-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#what-you-have-to-do)
  - [Kexts Used](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#kexts-used)
  - [SSDTs Used](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#ssdts-used)
  - [Credits](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#-donate---ba%C4%9F%C4%B1%C5%9F-)

## Screenshot 📷
<details>
<summary>Big Sur & Mojave</summary>

![](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/Ventura.png)
![](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/BigSur.png)
![](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/Mojave.png)

</details>

## Original Hardware  💻
Type | Spec | Status
:---------|:---------|:----------
Model Name      | Lenovo Thinkpad Yoga S1 | ✅
CPU              | Intel(R) Core(TM) i7-4510U CPU @ 2.0GHz (max 3.10Ghz) Haswell | ✅
RAM           | 8 GB 2400 MHz DDR4 | ✅
Internal Graphics Card | Intel® HD Graphics 4400 | ✅
Wi-Fi             | Intel Wireless 7260 | ✅
Audio       | Conexant CX20751 | ✅

## macOS Update History
- ✅ macOS Ventura 13.3.1
- ✅ macOS Monterey 12.6.3
- ✅ macOS Monterey 12.6
- ✅ macOS Monterey 12.3
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.5.2
- ✅ macOS Big Sur 11.0.1

## What's working  💻
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅
Intel HD Graphics 4400              |  ✅
Brightness control                  |  ✅
Audio Conexant CX20751 (id:28)      |  ✅
3.5mm Combojack                     |  ✅
Intel 7260 Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅
USB 3.0 (with Port Map)        |  ✅
Touchpad (14 gestures are working)   |  ✅
Touchscreen with gestures           |  ✅
Battery status   |  ✅
Camera   |  ✅
Shutdown / Reboot   |  ✅
Fn shortcut keys   |  ✅
Sleep/Wake   |  ✅

## What's not working  💻
Type | Status
:---------|:---------
Airdrop, Sidecar (Beacuse Intel Wi-Fi)   | ❌

## What You Have to Do?
Type | | Status
:---------|:---------:|---------
SMBIOS Settings  | MacBook Pro 11,1 | ⚠️

## Kexts Used
Name | Info
:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that parses battery info.
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that provides power info of processor temperature.
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[ECEnabler](https://github.com/1Revenger1/ECEnabler) | Allows reading Embedded Controller fields over 1 byte long, vastly reducing the amount of ACPI modification needed (if any) for working battery status.	
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[USBWakeFixup.kext](https://github.com/osy/USBWakeFixup) | This extension is a workaround for that issue by creating a fake ACPI device with the right wakeup params.	
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.
[VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) | VoodooI2C is a project consisting of macOS kernel extensions that add support for I2C bus devices.
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS.	
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.	
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware on Monterey+.
[USBPorts](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports.



## SSDTs Used
  
Name | Info | Status
:---------|:---------|:---------
[SSDT-EC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC). | [Functional]
[SSDT-EXT1-FIXSHUTDOWN.aml](https://github.com/5T33Z0/OC-Little-Translated/blob/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix/SSDT-EXT1-FixShutdown.dsl) | EXT1 Extension patch. Fixes the reboot problem after shutfown caused by the XHC Controller by setting XHC.PMEE to 0 when the parameter passed in _PTS is 5. This patch has the same effect as Clover's FixShutdown. Some Dell XPS and ThinkPads will require this patch. | [Functional]
[SSDT-GPRW](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html) | macOS will instant wake if either USB or power states change while sleeping. To fix this we need to reroute the GPRW/UPRW/LANC calls to a new SSDT. | [Functional]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-LAN.aml](https://5t33z0.gitbook.io/oc-litte-translated/oc-little/enabling-devices-and-features-via-ssdts/ethernet/fake-ethernet-controller-null-ethernet) | Some machines don't have have a native Ethernet port (which is rare), but you can spoof one with this SSDT and a kext. | [Functional]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PNLF.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | [Functional]
[SSDT-USBW.aml](https://github.com/osy/USBWakeFixup) | On systems without a working Embedded Controller, waking up from a USB device might not wake up the display. A second key-press or mouse click is required to wake up the display. This extension is a workaround for that issue by creating a fake ACPI device with the right wakeup params. | [Functional]



## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
