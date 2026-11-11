# 🎓 Kartu Ucapan Selamat Hari Guru

Kartu ucapan interaktif pure **HTML + CSS** untuk memperingati **Hari Guru Nasional**.

Inspirasi desain diambil dari kartu Valentine klasik dengan awan, hati mengambang, dan efek hover yang mengubah teks menjadi pesan motivasi.

## ✨ Fitur

- Desain soft pastel yang elegan
- Hati animasi mengambang ke atas
- Efek *hover* → halaman 1 berubah menjadi pesan penyemangat
- Fully responsive
- Tidak membutuhkan JavaScript

## 📱 Cara Menggunakan

1. Buka file `index.html` di browser
2. Arahkan kursor ke kartu untuk melihat pesan motivasi
3. Atau deploy ke GitHub Pages / Netlify / Vercel

## 🛠️ Struktur File

```
kartu-ucapan-hari-guru/
├── index.html
├── style.css
└── README.md
```

## 🎨 Kustomisasi

Semua warna disimpan di CSS variables (`:root`) sehingga mudah diganti sesuai selera.

Pesan di halaman kedua bisa diubah di bagian:

```css
.text:hover::before {
  content: "Pesan barumu di sini...";
}
```

## 📅 Hari Guru Nasional

Diperingati setiap **25 November**.

Tema 2026: **"Guru Hebat, Indonesia Kuat"**

---

Dibuat dengan ❤️ untuk para guru hebat.
