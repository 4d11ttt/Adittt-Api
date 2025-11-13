<h1 align="center">Adittt-Api</h1>
<p align="center">
  Sebuah REST API gratis tanpa perlu API key, menyediakan berbagai fitur untuk developer.
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/4d11ttt/Adittt-Api?style=social" alt="GitHub Stars">
  <img src="https://img.shields.io/github/forks/4d11ttt/Adittt-Api?style=social" alt="GitHub Forks">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Language-JavaScript-yellow" alt="Language">
  <img src="https://img.shields.io/badge/Status-Aktif-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/API%20Key-Tidak%20Perlu-success" alt="API Key">
</p>

---

## 📋 Daftar Isi

* [📖 Tentang Proyek](#-tentang-proyek)
* [✨ Fitur Utama](#-fitur-utama)
* [🚀 Cara Menggunakan](#-cara-menggunakan)
* [💻 Instalasi (Self-Host)](#-instalasi-self-host)
* [🤝 Kontribusi](#-kontribusi)
* [📄 Lisensi](#-lisensi)

---

## 📖 Tentang Proyek

**Adittt-Api** adalah sebuah REST API publik yang dibuat dengan Node.js dan Express. Didesain agar mudah digunakan, API ini tidak memerlukan kunci (API key) dan menyediakan puluhan endpoint yang berguna untuk berbagai keperluan, seperti bot WhatsApp, aplikasi web, atau proyek hobi lainnya.

## ✨ Fitur Utama

API ini mencakup berbagai kategori, di antaranya:

* **Downloader:** Mengunduh konten dari berbagai platform (seperti YouTube, TikTok, Instagram, dll.)
* **Search:** Melakukan pencarian (Google, gambar, lirik).
* **Anime:** Informasi dan gambar terkait anime.
* **Maker:** Membuat gambar atau teks (cth: TextPro, Ephoto360).
* **Game:** Endpoint untuk fitur game (cth: tebak gambar).
* **Islamic:** Konten Islami (jadwal sholat, Al-Qur'an).
* **Stalker:** Mendapatkan info dari profil media sosial.
* **Random:** Konten acak (fakta, lelucon, gambar).
* ...dan masih banyak lagi!

## 🚀 Cara Menggunakan

Anda bisa langsung mengakses endpoint yang tersedia menggunakan `BASE_URL` dari API ini.

**Struktur Request:**
`[BASE_URL]/[kategori]/[endpoint]?[parameter]`

**Contoh (Request Sederhana):**
```bash
# Menggunakan curl
curl "[https://url-api-anda.com/api/search/google?q=Apa%20itu%20Node.js](https://url-api-anda.com/api/search/google?q=Apa%20itu%20Node.js)"

# Menggunakan fetch di JavaScript
fetch('[https://url-api-anda.com/api/search/google?q=Apa](https://url-api-anda.com/api/search/google?q=Apa) itu Node.js')
  .then(res => res.json())
  .then(data => console.log(data));
