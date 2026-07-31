# 🎁 Website Ulang Tahun - Birthday Love Website

Website ucapan ulang tahun yang indah, romantis, dan interaktif. Dibuat khusus untuk membuat hari spesial orang yang Anda sayangi menjadi tak terlupakan.

## ✨ Fitur Utama

✅ **Desain Romantis** - Gradient warna pink & ungu yang elegan  
✅ **Animasi Smooth** - Transisi & efek yang memukau  
✅ **Responsive Design** - Terlihat bagus di semua device  
✅ **Interactive Elements** - Button confetti yang meriah  
✅ **Loading Optimized** - Cepat & tidak berat  
✅ **Dark Mode** - Tema gelap yang nyaman di mata  

## 🚀 Quick Start

### Untuk Testing Lokal
```bash
# Buka langsung di browser
# Klik kanan file "birthday-love.html" → Open with Browser
```

### Untuk Deploy ke Vercel

1. **Buat GitHub Account** (jika belum punya)
   - Buka github.com
   - Daftar gratis

2. **Push ke GitHub**
   ```bash
   git clone https://github.com/anda/repo-name
   cd repo-name
   # Masukkan file HTML, package.json, vercel.json
   git add .
   git commit -m "Add birthday website"
   git push
   ```

3. **Deploy ke Vercel**
   - Buka vercel.com
   - Login dengan GitHub
   - Click "New Project"
   - Pilih repository Anda
   - Click "Deploy"
   - ✅ Done! Website live dalam hitungan detik

## 🎨 Cara Customize

### 1️⃣ Edit Text & Nama

Buka `birthday-love.html` dan cari:

```html
<!-- GANTI BAGIAN INI -->
<h1>Selamat Ulang Tahun!</h1>
<p class="subtitle">Hari spesial untuk orang yang paling spesial</p>
<p class="tagline">Semoga setiap momen hari ini membawa kebahagiaan...</p>
```

Contoh custom:
```html
<h1>Selamat Ulang Tahun, Siti! 🎂</h1>
<p class="subtitle">24 Tahun Lebih Cantik & Baik Hati</p>
<p class="tagline">Setiap hari bersamamu adalah berkah ✨</p>
```

### 2️⃣ Edit Pesan di Card

Cari bagian "Message Cards" dan edit 3 card:

```html
<div class="card">
    <span class="card-icon">🌟</span>
    <h3 class="card-title">JUDUL CARD</h3>
    <p class="card-text">ISI PESAN ANDA DI SINI...</p>
</div>
```

### 3️⃣ Ubah Warna & Tema

Warna utama ada di CSS:

```css
background: linear-gradient(135deg, #ff69b4, #ff1493, #ff69b4);
/* 
   #ff69b4 = Pink muda
   #ff1493 = Pink terang
   
   Ganti dengan warna favorit:
   #ff6b9d = Pink neon
   #c2185b = Pink tua
   #e91e63 = Pink vibrant
   #9c27b0 = Purple
*/
```

Cari warna di: https://www.color-hex.com

### 4️⃣ Tambah Foto (Advanced)

Di folder GitHub yang sama dengan HTML, upload foto Anda:

```html
<section class="gallery-section">
    <h2 class="gallery-title">Kenangan Indah Kita ❤️</h2>
    <img src="foto1.jpg" alt="Bersama" 
         style="max-width: 300px; border-radius: 15px; margin: 20px 0;">
    <img src="foto2.jpg" alt="Senyuman" 
         style="max-width: 300px; border-radius: 15px; margin: 20px 0;">
</section>
```

## 📁 File Structure

```
birthday-love/
├── birthday-love.html    ← File utama (buka di browser)
├── package.json          ← Konfigurasi project
├── vercel.json          ← Konfigurasi Vercel
├── .gitignore           ← Git ignore file
├── README.md            ← File ini
└── PANDUAN_SETUP.md     ← Panduan detail setup
```

## 🔗 Share ke Pacar

Setelah deploy ke Vercel, Anda akan dapat URL seperti:
```
https://birthday-love-[random-id].vercel.app
```

Kirim via:
- WhatsApp 💬
- Email 📧
- Social Media 📱
- Buat QR Code 📲

## 🎯 Testing Checklist

- [ ] Buka di Chrome (desktop)
- [ ] Buka di Safari (desktop)
- [ ] Buka di Mobile (Chrome/Safari)
- [ ] Klik button "Buat Hari Ini Istimewa" → Ada confetti ✨
- [ ] Alert berisi pesan ❤️

## ⚡ Tips & Tricks

### Pasang Background Music
```html
<!-- Tambahkan sebelum </body> -->
<audio autoplay loop>
    <source src="lagu.mp3" type="audio/mpeg">
</audio>
```

### Ubah Font
Di CSS, cari `@import url` dan ganti Google Fonts:
- Fonts tersedia: fonts.google.com

### Countdown Timer (Advanced)
Hubungi developer untuk menambah countdown ke hari ulang tahun berikutnya

### Tambah Video
```html
<iframe width="100%" height="400" 
    src="https://www.youtube.com/embed/VIDEO_ID" 
    style="border-radius: 15px; margin: 20px 0;">
</iframe>
```

## 🐛 Troubleshooting

### Website tidak muncul?
- ✓ Pastikan Anda gunakan Chrome/Firefox modern
- ✓ Clear cache: Ctrl+Shift+Delete
- ✓ Refresh: Ctrl+F5

### Animasi tidak jalan?
- ✓ Browser tidak support? Upgrade Chrome/Firefox
- ✓ Device tua? Coba browser lain

### Deploy ke Vercel error?
- ✓ Pastikan semua file sudah di-push ke GitHub
- ✓ Repository harus public
- ✓ Tunggu 2 menit untuk build selesai

## 📞 Support

- Vercel Help: vercel.com/docs
- GitHub Help: github.com/support
- Font Issues: fonts.google.com
- Color Picker: color-hex.com

## 📜 License

Free to use & modify for personal use ❤️

---

## 🎉 Final Words

Website ini dibuat dengan cinta untuk membuat hari spesial menjadi lebih istimewa. Jangan lupa untuk:

1. ✏️ Customize dengan cerita Anda
2. 🎨 Pilih warna favorit
3. 📸 Tambah foto kenangan
4. 🎁 Kirim dengan hati
5. 💕 Rayakan bersama

**Selamat Ulang Tahun! 🎂🎉✨**

---

Made with ❤️ for special moments
