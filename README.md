# 💍 Undangan Digital Pernikahan

Template undangan pernikahan digital modern & minimalis berbasis HTML, CSS, dan JavaScript murni. Tanpa framework, ringan, dan mudah dikustomisasi.

🌐 **Live Demo:** [https://USERNAME.github.io/undangan-digital](https://USERNAME.github.io/undangan-digital)

---

## ✨ Fitur

- Cover halaman dengan animasi elegan
- Countdown timer otomatis menuju hari H
- Profil kedua mempelai
- Jadwal acara (Akad & Resepsi)
- Galeri foto pasangan
- Integrasi Google Maps lokasi
- Form ucapan & konfirmasi kehadiran
- Animasi scroll reveal
- Responsive mobile-friendly

---

## ✏️ Cara Kustomisasi

Buka `index.html` dan ubah bagian berikut:

| Yang diubah | Cari teks |
|---|---|
| Nama mempelai | `Rizky` dan `Amira` |
| Tanggal pernikahan | `14 Juni 2025` |
| Nama orang tua | `Ahmad Fauzi`, `Siti Rahayu`, dst |
| Lokasi acara | `Grand Ballroom Bumi Surabaya` |
| Alamat | `Jl. Jenderal Basuki Rahmat` |
| Link Google Maps | `src` pada tag `iframe` |
| Countdown target | `new Date('2025-06-14T08:00:00')` |

---

## 🖼️ Menambahkan Foto

Taruh foto di folder `images/` lalu ubah bagian galeri:
```html
<div class="gal-item" style="background-image:url('images/foto1.jpg')"></div>
```

---

## 🚀 Deploy ke GitHub Pages

1. Push ke GitHub
2. Settings → Pages → Branch: main → Save
3. Live di `https://USERNAME.github.io/undangan-digital`

---

## 🛠️ Teknologi

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript
- Google Maps Embed API
- Google Fonts (Playfair Display + DM Sans)
