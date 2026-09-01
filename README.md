# 🔗 TikTok Bio Link

Landing page modern untuk bio link TikTok. Desain dark mode dengan animasi smooth, responsif, dan siap deploy ke Vercel.

## 📁 Struktur Folder

```
tiktok-bio-link/
├── public/           ← Semua file statis di sini
│   ├── index.html
│   ├── style.css
│   └── script.js
├── vercel.json       ← Konfigurasi Vercel
├── package.json      ← Metadata project
└── README.md
```

## 🚀 Deploy ke Vercel

### Cara 1: Upload ke GitHub (Rekomendasi)
1. Extract zip ini
2. Buat repository baru di GitHub
3. Upload semua file & folder ke repo
4. Buka [vercel.com](https://vercel.com) → Login
5. Klik "Add New Project" → Import Git Repository
6. Pilih repo ini → Framework Preset: **Other**
7. Klik "Deploy"

### Cara 2: Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

## 📝 Kustomisasi

Edit `public/index.html`:

| Bagian | Yang diubah |
|--------|------------|
| Foto profil | `<img class="avatar" src="...">` |
| Nama | `<h1 class="name">Nama Kamu</h1>` |
| Username | `<p class="handle">@username</p>` |
| Bio | `<p class="bio">...</p>` |
| Link | Semua tag `<a href="...">` |
| Stats | `data-target="..."` |

---

Made with ❤️
