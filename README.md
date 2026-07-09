# SOLARIS | UM BBM–Desa Srigonco 2026

Website portal (seperti Linktree) untuk program UM BBM di Desa Srigonco tahun 2026.

## 🚀 Persiapan Sebelum Deploy

Sebelum mendeploy website ini (misalnya ke Vercel), pastikan Anda telah memasukkan link yang benar untuk tombol-tombol yang ada di file `index.html`.

1. Buka file `index.html`
2. Cari bagian `<div class="links">` (sekitar baris 200+)
3. Temukan baris dengan kode berikut:
   - **Video:** `<a class="link-card" href="#" target="_blank" rel="noopener noreferrer">`
   - **Form:** `<a class="link-card" href="#" target="_blank" rel="noopener noreferrer">`
4. Ganti tanda `#` pada bagian `href="#"` dengan link URL Anda (contoh: `href="https://youtube.com/..."`).

## 📁 File dalam Proyek Ini

- `index.html` - File utama yang berisi tampilan website (HTML + CSS).
- `vercel.json` - File konfigurasi untuk Vercel (mengatur *clean URLs* dan *security headers*).
- `robots.txt` - File standar SEO untuk memberikan instruksi kepada *search engine* (seperti Google) saat mengindeks website.

## 🌐 Cara Deploy ke Vercel

1. Buat akun di [Vercel](https://vercel.com/)
2. Install Vercel CLI (jika menggunakan terminal) atau deploy langsung dengan menghubungkan folder ini ke repository GitHub Anda melalui dashboard Vercel.
3. Vercel secara otomatis akan membaca `index.html` dan `vercel.json`.
