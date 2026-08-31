# ⚡ NEON VIPER // OVERDRIVE

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-00f3ff?style=for-the-badge" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/Status-Playable-00ff66?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Zero-Dependencies-ff0055?style=for-the-badge" alt="Dependencies">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-ffe600?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Hosted%20On-GitHub%20Pages-blueviolet?style=for-the-badge" alt="GitHub Pages">
</p>

<p align="center">
  <b>Neon Viper</b>, klasik yılan (Snake) mekaniğini alıp fütüristik siberpunk atmosferi, dinamik kombo zincirleri ve saf retro-arcade heyecanıyla yeniden yorumlayan bağımsız bir HTML5 tarayıcı oyunudur.
</p>

---

## 🎮 Canlı Demo (Live Preview)
Oyunu tarayıcınızda anında oynamak için GitHub Pages linkinizi buraya ekleyin:
👉 **[Neon Viper Oyna!](https://thee1even11.github.io/NEON-VIPER-OVERDRIVE/)**

---

## 🕹️ Nasıl Oynanır? (Controls)

### 💻 Masaüstü Kontrolleri
| Tuş | Eylem |
| :--- | :--- |
| **W, A, S, D** veya **Yön Tuşları** | Yılanı yönlendir |
| **SPACE** veya **SHIFT** (Basılı Tut) | **Hyper Boost** (Hızlanma) |
| **P** veya **ESC** | Oyunu Duraklat / Devam Et |
| **R** | Anında Yeniden Başlat (Restart) |

### 📱 Mobil & Dokunmatik Kontroller
- **Sanal D-Pad:** Ekranın sol altındaki yön tuşları ile yönlendirin.
- **Boost Düğmesi:** Sağ alttaki büyük neon butona basılı tutarak turbo hızına geçin.
- **Swipe (Kaydırma):** Ekranda parmağınızı hızlıca kaydırarak da dönüş yapabilirsiniz.

---

## 💎 Oyun Mekanikleri & Güçlendirmeler

- 🔵 **Cyan Orb (Standart Küre):** Kombo sayacınızı yeniler, boyunuzu uzatır ve skoru artırır.
- 🟡 **Super Nova (Sarı Elmas):** Sınırlı süre ekranda kalır. Yüksek skor verir ve Boost enerjinizi %100 doldurur.
- 🟣 **Ghost Phase (G Power-up):** Aktif olduğunda mor renge bürünürsünüz ve kendi kuyruğunuzun içinden yanmadan geçebilirsiniz.
- 🟢 **Magnet Field (M Power-up):** Küreleri kendinize doğru çeken manyetik bir çekim alanı oluşturur.
- 🔴 **Hyper Drive (H Power-up):** Kombo çarpanınızı anında tırmandırır.

---

## 🛠️ Teknik Özellikler

- **Tek Dosya Mimarisi:** Dışarıdan hiçbir görsel, kütüphane veya `.mp3` indirmez. HTML + CSS + JS tek bir `index.html` içindedir.
- **Web Audio API Sentezleyici:** Bütün ses efektleri (ısırık, bas patlamaları, boost uğultusu) gerçek zamanlı osilatörlerle sentezlenir.
- **Input Buffering (Girdi Tamponu):** Arka arkaya hızlı basılan tuşları kaçırmaz, dönüşleri sıraya koyar.
- **Yerel Lider Tablosu (Local Leaderboard):** En yüksek skorları ve kombo rekorlarını tarayıcınızın `localStorage` alanında saklar.
- **Akıllı Ekran Uyumu:** Yüksek DPI (Retina) ekranları destekleyen dinamik Canvas ölçeklendirmesi.

---

## 📜 Lisans
Bu proje **GPL 3.0 Lisansı** altında sunulmaktadır.
