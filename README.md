# 🔗 TikTok Bio Link

Landing page modern untuk bio link TikTok. Desain dark mode dengan animasi smooth, responsif, dan siap deploy ke Vercel.

## ✨ Fitur

- 🎨 Desain dark mode modern dengan gradient background
- 📱 Fully responsive (mobile-first)
- ⚡ Animasi smooth (counter, parallax, hover effects)
- 🔗 Link cards dengan icon dan shimmer effect
- 📊 Stats counter dengan format K/M
- 🎬 Featured video grid
- 🏷️ Verified badge animation
- 💫 Ripple effect on click

## 🚀 Deploy ke Vercel

### Cara 1: Drag & Drop (Termudah)
1. Buka [vercel.com](https://vercel.com) dan login
2. Klik "Add New..." → "Project"
3. Pilih "Import Git Repository" atau drag folder ini ke Vercel Dashboard
4. Klik "Deploy"
5. Selesai! Copy URL dan taruh di bio TikTok

### Cara 2: Via GitHub
1. Buat repository baru di GitHub
2. Upload semua file ke repository
3. Buka Vercel → Import Project → pilih repository
4. Framework Preset: **Other**
5. Klik "Deploy"

## 📝 Kustomisasi

Edit file berikut sesuai kebutuhan:

| File | Yang perlu diubah |
|------|------------------|
| `index.html` | Nama, username, bio, link, foto profil |
| `style.css` | Warna, font, spacing |
| `script.js` | Animasi, counter target |

### Ganti Foto Profil
Ganti URL di tag `<img class="avatar">` di `index.html` dengan URL foto kamu.

### Ganti Link
Cari semua tag `<a>` dan ganti `href` dengan link kamu.

### Ganti Stats
Ubah `data-target` di `.stat-num` dengan angka followers/likes/videos kamu.

## 📁 Struktur File

```
tiktok-bio-link/
├── index.html      # Halaman utama
├── style.css       # Styling & animasi
├── script.js       # Interaktivitas
├── vercel.json     # Konfigurasi Vercel
├── package.json    # Metadata project
└── README.md       # Dokumentasi
```

## 🎨 Preview

![Preview](https://via.placeholder.com/400x800/0a0a0f/ffffff?text=Preview)

---

Made with ❤️ for TikTok creators
