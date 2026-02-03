# Komiklin — Aplikasi Baca Manga 📱

<img src="https://i.ibb.co.com/GvHX1kTk/Komik.png" width="600" align-items=center; />

Komiklin adalah aplikasi Flutter untuk membaca manga dengan fitur lengkap: bookmark, riwayat baca, unduhan untuk dibaca offline, chat, komentar, teman, leaderboard, notifikasi push, serta login sosial.

## 🔗 Tautan & Akses

Kunjungi website resmi atau akses versi web melalui tautan berikut:

* **Website Resmi / Web App:** [https://komiklin.fun/](https://komiklin.fun/)
* **Unduh APK:** [https://komiklin.fun/](https://komiklin.fun/)

## ✨ Fitur Utama

* **Pengalaman Baca:** Mode baca horizontal/vertikal, *zoom*, dan antarmuka (UI) gelap yang nyaman.
* **Manajemen Pustaka:** Bookmark, riwayat baca otomatis, dan pencarian judul/komik yang responsif.
* **Mode Offline:** Unduh chapter pilihan untuk dibaca tanpa koneksi internet.
* **Interaksi Sosial:** Chat antar pengguna, kolom komentar, dan sistem permintaan pertemanan.
* **Notifikasi Cerdas:** Push notification (FCM) dengan *deep-link* yang langsung mengarah ke halaman manga atau chat relevan.
* **Autentikasi:** Login Google satu ketukan dan integrasi Supabase Auth yang aman.
* **Personalisasi:** Leaderboard, kustomisasi avatar pengguna, serta pengaturan tampilan navigasi.

## 🛠 Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan ekosistem **Flutter** yang kuat:

* **Framework & State:** Flutter (Material Design), Provider.
* **Backend & Auth:** Supabase Flutter, Google Sign In, Google APIs Auth.
* **Jaringan & Media:**
* `http`, `dio` (Networking)
* `cached_network_image` (Image Caching)
* `photo_view` (Zoomable Image)
* `just_audio` (Audio Support)
* `gallery_saver_plus` (Saving Media)


* **Notifikasi:** Firebase Core, Firebase Messaging, Flutter Local Notifications.
* **Utilitas:** Shared Preferences, Device Info Plus, Package Info Plus, Permission Handler, File Picker, Intl, Timeago.
