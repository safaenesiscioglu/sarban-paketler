<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-white.png">
  <img src="assets/logo-dark.png" alt="Sarban" width="140">
</picture>

# Sarban Paketleri

**Sarban uygulaması için çevrimdışı harita ve nokta paketleri**
*Offline map & point packs for the Sarban app*

[![Son sürüm](https://img.shields.io/github/v/release/safaenesiscioglu/sarban-paketler?label=son%20s%C3%BCr%C3%BCm&color=c8a165)](https://github.com/safaenesiscioglu/sarban-paketler/releases/latest)
[![İndirme](https://img.shields.io/github/downloads/safaenesiscioglu/sarban-paketler/total?label=indirme&color=2f3e46)](https://github.com/safaenesiscioglu/sarban-paketler/releases)
![İmzalı](https://img.shields.io/badge/imza-Ed25519-4a7c59)
![Veri](https://img.shields.io/badge/veri-OpenStreetMap-7ebc6f)

[Türkçe](#türkçe) · [English](#english) · [Deutsch](#deutsch) · [Русский](#русский) · [Українська](#українська) · [العربية](#العربية)

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

| Region | Map | Points | Status |
|---|---|---|---|
| 🇹🇷 Ankara | — | — | 🔜 In progress |
| 🇩🇪 Berlin | `berlin.pmtiles` (~79 MB) | `points_berlin.json` | ✅ Live |

**How to use:** Open Sarban → **Settings → Packs** → pick your region → **Download**. The app fetches the latest release automatically.

**Security:** Each release ships `index.json` (pack list + **SHA-256** of every file) and `index.json.sig` (**Ed25519** signature). The app verifies both before installing. No private key is stored here or in the app.

---

## Deutsch

Dieses Repository enthält die Inhaltspakete der App **Sarban**. Die Pakete werden in der App heruntergeladen und funktionieren danach vollständig offline.

| Region | Karte | Orte | Status |
|---|---|---|---|
| 🇹🇷 Ankara | — | — | 🔜 In Arbeit |
| 🇩🇪 Berlin | `berlin.pmtiles` (~79 MB) | `points_berlin.json` | ✅ Verfügbar |

**Nutzung:** Sarban öffnen → **Einstellungen → Pakete** → Region wählen → **Herunterladen**. Die App lädt automatisch die neueste Version.

**Sicherheit:** Jede Version enthält `index.json` (Paketliste + **SHA-256** jeder Datei) und `index.json.sig` (**Ed25519**-Signatur). Die App prüft beides vor der Installation. Kein privater Schlüssel liegt hier oder in der App.

---

## Русский

Этот репозиторий содержит пакеты данных для приложения **Sarban**. Пакеты загружаются в приложении и затем работают полностью без интернета.

| Регион | Карта | Точки | Статус |
|---|---|---|---|
| 🇹🇷 Анкара | — | — | 🔜 Готовится |
| 🇩🇪 Берлин | `berlin.pmtiles` (~79 МБ) | `points_berlin.json` | ✅ Доступно |

**Как использовать:** откройте Sarban → **Настройки → Пакеты** → выберите регион → **Скачать**. Приложение автоматически берёт последнюю версию.

**Безопасность:** каждая версия содержит `index.json` (список пакетов + **SHA-256** каждого файла) и `index.json.sig` (подпись **Ed25519**). Приложение проверяет их перед установкой. Закрытый ключ не хранится ни здесь, ни в приложении.

---

## Українська

Цей репозиторій містить пакети даних для застосунку **Sarban**. Пакети завантажуються в застосунку і далі працюють повністю без інтернету.

| Регіон | Мапа | Точки | Статус |
|---|---|---|---|
| 🇹🇷 Анкара | — | — | 🔜 Готується |
| 🇩🇪 Берлін | `berlin.pmtiles` (~79 МБ) | `points_berlin.json` | ✅ Доступно |

**Як користуватися:** відкрийте Sarban → **Налаштування → Пакети** → оберіть регіон → **Завантажити**. Застосунок автоматично бере останню версію.

**Безпека:** кожна версія містить `index.json` (список пакетів + **SHA-256** кожного файлу) та `index.json.sig` (підпис **Ed25519**). Застосунок перевіряє їх перед встановленням. Закритий ключ не зберігається ні тут, ні в застосунку.

---

## العربية

<div dir="rtl">

يحتوي هذا المستودع على حزم المحتوى لتطبيق **Sarban**. تُنزَّل الحزم من داخل التطبيق، وتعمل بعد ذلك بالكامل دون إنترنت.

| المنطقة | الخريطة | النقاط | الحالة |
|---|---|---|---|
| 🇹🇷 أنقرة | — | — | 🔜 قيد الإعداد |
| 🇩🇪 برلين | `berlin.pmtiles` (~79 ميغابايت) | `points_berlin.json` | ✅ متاحة |

**طريقة الاستخدام:** افتح Sarban ← **الإعدادات ← الحزم** ← اختر منطقتك ← **تنزيل**. يجلب التطبيق أحدث إصدار تلقائيًا.

**الأمان:** يتضمن كل إصدار الملف `index.json` (قائمة الحزم + بصمة **SHA-256** لكل ملف) والملف `index.json.sig` (توقيع **Ed25519**). يتحقق التطبيق منهما قبل التثبيت. لا يُحفظ أي مفتاح خاص هنا أو في التطبيق.

</div>

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
