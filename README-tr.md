<!-- omit in toc -->
#  Lenovo Thinkpad Yoga S1 üzerinde macOS

<h3> 
    <a href="https://github.com/relaxewdy/Lenovo-Yoga-S1-Hackintosh/blob/main/README.md">İngilizce</a>
    | Türkçe
</h3>

<img align="right" src="https://i.loli.net/2021/02/18/yip3eNsQWUZlFkd.png" width="400px" alt="preview">

Lenovo Thinkpad Yoga S1 için OpenCore config dosyası

[![macOS](https://img.shields.io/badge/macOS-11.2-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.6-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/Lenovo-Yoga-S1-Hackintosh/releases)

## Ekran Görüntüsü
<details>
<summary>Big Sur</summary>

![](https://i.loli.net/2021/02/18/Kpv5x1JmXozOnPU.png)

</details>

<!-- omit in toc -->
## Donanım

| **Lenovo** | Detaylar                                                 |
| ------------------- | ------------------------------------------- |
| Model İsmi      | Lenovo Thinkpad Yoga S1      |
| İşlemci              | Intel(R) Core(TM) i7-4510U CPU @ 2.0GHz (max 3.10Ghz) Haswell             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Dahili Grafik Kartı | Intel® HD Graphics 4400                     |
| Wi-Fi             | Intel Wireless 7260 |
| Ses       | Conexant CX20751                       |

## Neler Çalışıyor

- Turbo hızlandırma ve İşlemci Frekansı.
- Intel® HD Graphics 4400
  - Parlaklık Kontrolü
- Ses Conexant CX20751 
  - layout-id: `28`
  - 3.5mm Jak Girişi
- Intel Wireless 7260 Wi-Fi and Bluetooth (Handoff çalışıyor)
- USB Portları (Port Mapping yapıldı)
- Touchpad (14 harekette çalışıyor)
- Batarya Durumu
- Kamera
- Fn kısayol tuşları

## Neler Çalışmıyor

- Uyku / Uyanma
 
Kesinlikle OpenCore Configrator ile SMBIOS ayarlarınızı yapın çünkü config dosyası her hangi bir SMBIOS bilgisi içermiyor.
  - MacBook Pro 11,1
