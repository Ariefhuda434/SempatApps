# 🍱 SempatApps (SEMPAT)
> **S**elamatkan **E**nergi & **M**akanan, **P**eduli **A**ntar **T**etangga  
> *Smart Food Surplus Rescue & Donation Platform powered by Kotlin & AI Camera*

[![Kotlin](https://img.shields.io/badge/Kotlin-2.0+-7F52FF.svg?logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Android](https://img.shields.io/badge/Platform-Android-3DDC84.svg?logo=android&logoColor=white)](https://developer.android.com)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4.svg?logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![AI Powered](https://img.shields.io/badge/AI-Vision%20%26%20Camera-FF6F00.svg?logo=google&logoColor=white)](https://ai.google.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📌 Latar Belakang & Visi (Vision & Purpose)

Di satu sisi, setiap hari berton-ton makanan layak konsumsi dari restoran, toko roti, katering, supermarket, maupun rumah tangga terbuang sia-sia (*food surplus / food waste*). Di sisi lain, masih banyak saudara-saudara kita yang mengalami kesulitan mendapatkan asupan makanan harian.

**SempatApps** hadir sebagai jembatan sosial berbasis teknologi:
1. **Mencegah Food Waste**: Membantu pelaku usaha & individu mendistribusikan kelebihan makanan layak makan sebelum terbuang.
2. **Menuntaskan Kelaparan**: Memudahkan masyarakat prasejahtera, panti asuhan, dan relawan mendapatkan akses makanan gratis atau bersubsidi secara bermartabat.
3. **Pencatatan Cerdas dengan AI Camera**: Pengguna tidak perlu repot mengetik detail makanan; cukup foto makanan, AI akan langsung mendeteksi jenis makanan, porsi, perkiraan masa simpan, dan membuatkan draf donasi otomatis.

---

## ✨ Fitur Utama (Core Features)

### 📸 1. AI Camera Smart Food Listing
- **Instant Food Recognition**: Cukup arahkan kamera ke makanan surplus (sayur, roti, nasi kotak, buah, dll.).
- **Auto-Fill Details**: Model AI otomatis mengenali nama makanan, kategori, estimasi porsi, dan rekomendasi tanggal kedaluwarsa/kelayakan.
- **Safety & Freshness Check**: AI memberikan indikator panduan apakah makanan masih layak dibagikan.

### 🎁 2. Fitur Donasi & Rescue (Donation & Rescue Marketplace)
- **100% Free Donation**: Donasi langsung makanan gratis untuk yang membutuhkan atau organisasi sosial.
- **Rescue Surprise Bag**: Pilihan bagi resto/toko roti menjual paket surplus berkualitas dengan potongan harga besar (rescue bag).
- **Scheduled Pickup & Delivery**: Sistem penjadwalan pengambilan makanan agar tetap higienis dan tepat waktu.

### 📍 3. Peta Terdekat & Notifikasi Real-time (Nearby Geolocation)
- Peta interaktif berbasis lokasi untuk menemukan donasi makanan terdekat.
- Notifikasi push langsung saat ada donatur membagikan makanan di radius sekitar pengguna/relawan.

### 🤝 4. Verifikasi Komunitas & Relawan (NGO & Volunteer Network)
- Jalur khusus untuk panti asuhan, lembaga amal, dan komunitas sosial terverifikasi untuk mengklaim donasi dalam jumlah besar.
- Sistem reputasi donatur dan penerima untuk menjaga kebersihan dan ketertiban.

### 🌱 5. Impact Tracker (Jejak Kebaikan & Lingkungan)
- Melacak total kilogram makanan yang berhasil diselamatkan.
- Mengkalkulasi reduksi emisi karbon (CO₂e) yang dicegah dari pembuangan sampah organik.
- Total porsi makanan yang tersalurkan kepada penerima manfaat.

---

## 🏗️ Arsitektur & Tech Stack

Aplikasi ini dikembangkan menggunakan standar modern Android Development:

```
SempatApps/
├── app/
│   ├── src/main/java/com/sempatapps/
│   │   ├── core/               # Theme, common utilities, base components
│   │   ├── data/               # Repositories, API services, Room DB, DTOs
│   │   ├── domain/             # Use cases, domain models, repository interfaces
│   │   ├── presentation/       # Jetpack Compose UI (Screens, ViewModels, States)
│   │   │   ├── camera/         # AI Camera capture & recognition preview
│   │   │   ├── home/           # Feed of food donations & rescue items
│   │   │   ├── donation/       # Create donation, claim flow, tracking
│   │   │   ├── map/            # Nearby food radar & pickup points
│   │   │   └── profile/        # Impact stats & user settings
│   │   └── di/                 # Dependency injection modules (Hilt)
```

| Layer | Teknologi |
|---|---|
| **Language** | Kotlin 2.0+ |
| **UI Framework** | Jetpack Compose + Material Design 3 |
| **Architecture** | MVVM + Clean Architecture |
| **Asynchronous** | Kotlin Coroutines & Flow |
| **Dependency Injection** | Dagger Hilt |
| **AI / Computer Vision** | Google Gemini Multimodal API / ML Kit Vision |
| **Camera** | CameraX |
| **Networking** | Retrofit / Ktor Client + Kotlinx Serialization |
| **Local Database** | Room Database + Preferences DataStore |
| **Maps & Location** | Google Maps Compose / Play Services Location |

---

## 🚀 Rencana Pengembangan (Roadmap)

- [x] **Inisialisasi Project & Konsep Arsitektur**
- [ ] **Setup Skeleton Android Project (Gradle, Jetpack Compose, Hilt)**
- [ ] **Modul CameraX + AI Vision (Gemini / ML Kit)**
- [ ] **Screen Listing Donasi & Detail Makanan**
- [ ] **Sistem Autentikasi (Donatur, Penerima, Organisasi Amal)**
- [ ] **Integrasi Geolocation & Nearby Radar**
- [ ] **Fitur Klaim Donasi & QR Code Handover**
- [ ] **Dashboard Impact Tracker (Porsi Makanan & CO₂e)**

---

## 👨‍💻 Kontribusi & Author

Kelompo 6
---
*Sempat: Setiap Makanan Punya Kesempatan*
