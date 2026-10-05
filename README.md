<div align="center">
<h1>CS2-DMA — Counter-Strike 2 DMA Araştırma Framework</h1>

<p>
Counter-Strike 2 ile Direct Memory Access (DMA) etkileşimi için açık kaynaklı yazılım framework'ü. Bellek okuma, oyun entity parse, ağ senkronizasyonu ve veri görselleştirme metodolojilerini içerir. Düşük seviye programlama, PCIe mimarisi ve tersine mühendislik tekniklerini incelemek için pratik bir platform.
</p>

<p>
<strong>Bu proje eğitim ve araştırma amaçlıdır</strong><br>
Harici bir yöntemdir ve çalışması için <a href="https://github.com/ufrisk/pcileech-fpga">DMA Kartı</a> gereklidir.
</p>
</div>

---

## Özellikler

- **Bellek Okuma** — DMA kartı üzerinden CS2 süreç belleğine doğrudan erişim
- **Entity Parse** — oyuncu konumları, sağlık, silah bilgileri, takım verileri
- **Ağ Senkronizasyonu** — çoklu PC kurulumu için veri aktarımı
- **Veri Görselleştirme** — radar, ESP ve harita üzerinde canlı veri
- **PCIe Araştırma** — DMA kartı firmware'ı ve PCIe protokol deneyleri

## Gereksinimler

- DMA kartı (pcileech uyumlu FPGA)
- İkinci PC (DMA okuma için)
- Windows 10/11
- Visual Studio 2022+

## Derleme

```bash
# Visual Studio ile çözümü aç
# KevqDMA.slnx → Release x64 → Build
```

## Yapı

```
src/           — kaynak kod
include/       — başlık dosyaları
docs/          — dokümantasyon
```

---

## İletişim

Discord: [https://discord.gg/vU7PNVr8vk](https://discord.gg/vU7PNVr8vk)
