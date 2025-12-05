# 🚀 TJ SOSMED TOOLS

![TJ Sosmed Tools Logo](https://tiangjauh.web.id/book/logo.PNG)

> **All-in-One Web Tools untuk Konten Kreator & Fotografer.**
>
> *Download media, edit foto massal, analisa metadata, hingga riset konten dalam satu dashboard.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📖 Tentang Project

**TJ SOSMED TOOLS** adalah kumpulan *web-based utilities* yang dirancang untuk mempermudah workflow konten kreator, khususnya fotografer. Aplikasi ini berjalan secara **Client-Side** (di browser) untuk pemrosesan gambar, menjadikannya cepat dan aman karena foto Anda tidak diunggah ke server pihak ketiga (kecuali fitur Downloader yang menggunakan API).

Dikembangkan oleh **Ghaza Algifari** (Tiang Jauh Photography).

## ✨ Fitur Unggulan

### 📥 1. Universal Media Downloader
Download video dan foto tanpa watermark dari platform populer.
- **Support:** Instagram (Post, Reels, Story), TikTok (No Watermark), Facebook.
- **Teknologi:** Menggunakan RapidAPI (Universal Endpoint).

### 🎨 2. Auto Carousel Maker
Membuat *Microblog* atau *Carousel* Instagram 10 slide secara instan tanpa Photoshop/Canva.
- **Input:** Upload hingga 10 foto sekaligus.
- **Fitur:** Auto-resize (Square, Portrait 4:5, Story 9:16).
- **Template:**
  - *Minimalist Frame*
  - *Modern Split*
  - *Cinematic Dark*
  - *Aesthetic Film Journal*

### 💧 3. Auto Watermark (Batch)
Tempel logo branding ke banyak foto sekaligus dalam hitungan detik.
- **Batch Processing:** Proses 10+ foto sekaligus.
- **Kontrol:** Atur posisi (Grid 3x3), ukuran, dan transparansi secara *real-time*.
- **Smart Crop:** Opsi crop otomatis ke rasio sosmed (1:1, 4:5, 9:16).

### 🛡️ 4. Metadata Remover (Privacy)
Hapus jejak digital dari foto sebelum disebar ke internet.
- Menghapus data GPS (Geo-tagging), tipe kamera, dan tanggal pengambilan.
- Proses dilakukan 100% di browser menggunakan *Canvas Redrawing*.

### 👁️ 5. Metadata Viewer (EXIF)
Intip "jeroan" sebuah foto asli.
- Melihat Shutter Speed, ISO, Aperture, Lensa, hingga Lokasi GPS.
- Dilengkapi fitur pencarian data (Searchable Raw Data).

### 🤖 6. AI & Riset Konten
- **AI Trend Hunter:** Simulasi prediksi ide konten, musik viral, dan format video.
- **Live Ticker:** Running text berita viral & bencana terkini (Integrasi Google Trends RSS).
- **Caption AI:** Generator caption otomatis berdasarkan *tone* (Lucu, Bijak, Promosi).
- **Hashtag Riset:** Database hashtag *Hard/Medium/Niche* untuk berbagai kategori.

---

## 🛠️ Teknologi yang Digunakan

* **Frontend:** HTML5, CSS3 (Grid/Flexbox), Vanilla JavaScript (ES6+).
* **External Libraries:**
    * `exif-js` (Untuk membaca Metadata).
    * `FontAwesome 6` (Untuk ikon UI).
* **API:**
    * RapidAPI (*Social Media Video Downloader*).
    * AllOrigins (*CORS Proxy* untuk Google Trends).

---

## 📂 Struktur Folder

```text
TJ-SOSMED-TOOLS/
│
├── index.html          # Dashboard Utama & Live Ticker
├── downloader.html     # Halaman Media Downloader
├── remover.html        # Halaman Metadata Remover
├── viewer.html         # Halaman Metadata Viewer
├── caption.html        # Halaman AI Caption
├── hashtag.html        # Halaman Hashtag Riset
├── watermark.html      # Halaman Auto Watermark
├── carousel.html       # Halaman Auto Carousel
├── acknowledgment.html # Halaman Dedikasi
├── style.css           # Styling Global (Dark Mode)
├── script.js           # Logic Utama (All-in-One)
└── README.md           # Dokumentasi
