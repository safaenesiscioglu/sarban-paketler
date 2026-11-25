<div align="center">

# 🐪 Sarban Paketleri

**Sarban uygulaması için çevrimdışı harita ve nokta paketleri**
*Offline map & point packs for the Sarban app*

[![Son sürüm](https://img.shields.io/github/v/release/safaenesiscioglu/sarban-paketler?label=son%20s%C3%BCr%C3%BCm&color=c8a165)](https://github.com/safaenesiscioglu/sarban-paketler/releases/latest)
[![İndirme](https://img.shields.io/github/downloads/safaenesiscioglu/sarban-paketler/total?label=indirme&color=2f3e46)](https://github.com/safaenesiscioglu/sarban-paketler/releases)
![İmzalı](https://img.shields.io/badge/imza-Ed25519-4a7c59)
![Veri](https://img.shields.io/badge/veri-OpenStreetMap-7ebc6f)

[Türkçe](#türkçe) · [English](#english)

</div>

---

## Türkçe

Bu depo, **Sarban** uygulamasının indirdiği içerik paketlerini barındırır. Paketler uygulama içinden indirilir. Bir kez indirdikten sonra internet olmadan çalışır.

### 📦 Mevcut paketler

| Bölge | Harita | Noktalar | Durum |
|---|---|---|---|
| 🇹🇷 Ankara | — | — | 🔜 Hazırlanıyor |
| 🇩🇪 Berlin | `berlin.pmtiles` (~79 MB) | `points_berlin.json` | ✅ Yayında |

Noktalar: hastane, eczane, toplanma alanı, su, sığınak vb.

### 📲 Nasıl kullanılır?

1. Sarban'ı aç → **Ayarlar → Paketler**
2. Bölgeni seç → **İndir**
3. İndirme bitince internet gerekmez.

> Uygulama paketleri bu deponun **son sürümünden** (Releases) otomatik çeker. Elle indirmen gerekmez.

### 🔒 Güvenlik

Her sürümde:

- `index.json`: paket listesi, sürüm ve her dosyanın **SHA-256** özeti
- `index.json.sig`: listenin **Ed25519** imzası

Uygulama önce imzayı, sonra her dosyanın özetini kontrol eder. Biri tutmazsa paket **kurulmaz**. Gizli anahtar bu depoda veya uygulamada bulunmaz.

### 🗓️ Sürümler

Sürüm adları tarihtir: `vYYYY.AA.GG` (ör. `v2026.11.22`). Her sürüm **değişmez**, güncelleme her zaman yeni sürüm olarak çıkar.

---

## English

This repository hosts the content packs downloaded by the **Sarban** app. Packs are downloaded inside the app and work fully offline afterwards.

### 📦 Available packs

| Region | Map | Points | Status |
|---|---|---|---|
| 🇹🇷 Ankara | — | — | 🔜 In progress |
| 🇩🇪 Berlin | `berlin.pmtiles` (~79 MB) | `points_berlin.json` | ✅ Live |

### 📲 How to use

Open Sarban → **Settings → Packs** → pick your region → **Download**. The app fetches the **latest release** automatically.

### 🔒 Security

Each release ships `index.json` (pack list + **SHA-256** of every file) and `index.json.sig` (**Ed25519** signature). The app verifies the signature and every hash before installing. No private key is stored here or in the app.

---

## 📄 Lisans / License

- Depodaki **kod ve betikler**: [MIT](LICENSE)
- **Harita ve nokta verileri**: © [OpenStreetMap](https://www.openstreetmap.org/copyright) katkıcıları, [ODbL 1.0](https://opendatacommons.org/licenses/odbl/) lisansıyla
  *Map & point data © OpenStreetMap contributors, licensed under ODbL 1.0*

---

<div align="center">

**Sarban**: çevrimdışı acil durum ve bilgi uygulaması · *offline emergency & knowledge app*

Destek / Support: [contact@safaenesiscioglu.com](mailto:contact@safaenesiscioglu.com) ·
Bağış / Donate: [PayPal](https://www.paypal.com/paypalme/safaenesiscioglu)

</div>
