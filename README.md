# Lenovo V330-14IKB 14" | Intel i5 (8250U)

[![macOS](https://img.shields.io/badge/macOS-11.4-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.0-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/indir-son%20sürüm-blue.svg)](https://github.com/sutsurup/Lenovo-V330-Hackintosh/releases)

<img align="right" src="Images/Lenovo-V330.png" alt="Lenovo" height="260" width="363">

Türkçe | [English](README_EN.md)

**macOS Sürümü: 11.4**

**OpenCore Sürümü: 0.7.0**

Yardımcı olabilecek kaynaklar: 

- [OpenCore Yükleme Rehberi](https://dortania.github.io/OpenCore-Install-Guide)


# Detaylar

    Tarih:        21 Mayıs 2021
    Durum:        Stabil
    Destek:       BIOS (429.100.7.0.0)
    Yapı:         OpenCore

## Donanım

| **LENOVO** | Detay                                                  |
| ------------------- | ------------------------------------------- |
| Model Adı      | Lenovo V330-14IKB      |
| Anakart           | 	Lenovo V330     |
| CPU              | Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz KabyLake R              |
| RAM           | 2400 MHz Tümleşik 4 GB + BigBoy 8GB DDR4 2666 MHz SODIMM (Toplam: 12GB)   |
| Dahili Grafik Kartı | Intel(R) UHD Graphics 620 (1 GB)                    |
| Wi-Fi | Intel(R) Dual Band Wireless-AC 3165                |
| Ses Kartı       | Conexant CX20751/2 (Layout: 3)                        |
| BIOS Sürümü      | 429.100.7.0.0                   |

![](Screenshots/info.png)

## Uyumluluk
**macOS Big Sur 11.4** sürümünde kararlı olarak çalışmaktadır. 11.4 ve altı sürümlere güncelleme yapabilirsiniz.
Doğrudan 11.4 sürümü yüklenemediği için, orijinal Apple dosyaları ile önce 10.15.7 (Catalina) sürümüne temiz kurulum yapılmış, ardından 11.4 (Big Sur) sürümüne güncellenmiştir.
Releases bölümünde EFI klasörünü içeren bir zip dosyası paylaştım. macOS kurulum belleğinizdeki EFI bölümüne, zip içerisindeki BOOT ve OC klasörlerini kopyalayınız.
macOS High Sierra 10.13.6, Mojave 10.14.6, Catalina 10.15.7 ve Big Sur 11.4 sürümlerinde çalıştırmayı deneyebilirsiniz.

### Çalışan Donanımlar

- [x] Uyku Modu
- [x] Ethernet (Yamalı)
- [x] Wi-Fi + Bluetooth (openIntelWireless, HeliPort olmadan)
- [x] Ses ve Mikrofon (Layout: 3)
- [x] Batarya yüzde göstergesi

### Çalışmayan Donanımlar
- [ ] Ekran parlaklığı
- [ ] HDMI (Tam olarak çalışmıyor)

![](Screenshots/update.png)

## Kurulum Sonrası Yararlı Rehberler
* **Önerilir:** iCloud, iMessage veya FaceTime kullanmak istiyorsanız, bu rehberi harfiyen uygulayın: [OpenCore ile iMessage ve Apple Servislerini Aktif Etmek](https://osxinfo.net/konu/opencore-ile-imessage-ve-apple-servislerini-aktif-etmek.16297/) (Bu rehberde Clover Configurator gösterilmiş olsa da, siz OpenCore Configurator kullanarak adımları takip edebilirsiniz.)
* [ProperTree](https://osxinfo.net/konu/propertree-opencore-bootloader-icin-config-duzenleyici.12919/) (config.plist dosyasını düzenlemek için)
* Hackintool ([Forum Konusu](https://www.insanelymac.com/forum/topic/335018-hackintool-v286/) | [Direkt İndirme](http://headsoft.com.au/download/mac/Hackintool.zip)) (Detaylı sistem bilgisi ve düzenlemeler için)

## İletişim
Herhangi bir sorunla karşılaşırsanız, öncelikle [GitHub Issues](https://github.com/sutsurup/Lenovo-V330-Hackintosh/issues) sayfası üzerinden destek alabilirsiniz. 
Diğer sorularınız için aşağıdaki kanalları kullanabilirsiniz:

- **Website:** [sutsurup.tr](http://sutsurup.tr)
- **Mail:** [veysel@sutsurup.tr](mailto:veysel@sutsurup.tr)

## Ekran Görüntüleri
![](Screenshots/BigSur.png)

</details>

## Destek Olun
Projeyi faydalı bulduysanız, kaynak oluşturma konusunda bana yardımcı olmak için bağış yapabilirsiniz:
```
₿ 1Q8CEMHTuecxPUJpEdpRiG6Bg2GVtzw4bN
``` 
<a href='https://github.com/sutsurup/sutsurup/blob/main/Donate.md'><img alt='Bağış' src='https://github.com/sutsurup/MSI-Hackintosh-Build/blob/main/Images/donate.png?raw=true' height='360px' width='375px'/></a>
```
QR koda tıklayarak alternatif bağış seçeneklerine ulaşabilirsiniz.
``` 
