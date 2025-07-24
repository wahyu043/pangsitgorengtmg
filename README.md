# 🥟 pangsitgorengtmg Landing Page

Ini adalah **landing page** latihan untuk brand *Pangsit Goreng TMG*, dibuat dengan **Tailwind CSS** (manual build, tanpa framework) dan di-deploy di [Vercel](https://vercel.com).

## 🚀 Fitur

- Layout modern, responsif (mobile & desktop friendly)
- Animasi soft, warna khas kuliner (kuning/oranye, gold)
- Hero/jumbotron dengan background dinamis
- Keunggulan/produk dalam card carousel horizontal (auto geser saat scroll)
- Section "Tentang Kami", Testimoni, CTA, FAQ, dan Footer custom
- Semua konten mudah diedit, bisa copywriting sendiri atau pakai dummy

## ⚡️ Cara Pakai

1. **Install dependency:**
   ```
   npm install
   ```
2. **Build Tailwind CSS:**
   ```
   npx tailwindcss -i ./src/input.css -o ./dist/output.css
   ```
3. **Edit konten:**  
   - Ubah gambar dan teks di `index.html`
   - Ganti link WhatsApp, produk, dsb
4. **Deploy:**  
   - Push ke GitHub
   - Connect ke [Vercel](https://vercel.com) dan deploy sebagai project statis

## 📦 Struktur Folder

```
/
├─ dist/              # CSS hasil build Tailwind
├─ img/               # Semua gambar/logo
├─ src/               # input.css utama Tailwind
├─ index.html         # Landing page utama
├─ tailwind.config.js # Konfigurasi Tailwind
├─ package.json
```

## 🙌 Credit & Kontributor

- Built with ❤️ by [Wahyu Mahmudiyanto](https://wahyu043.github.io/wahyumahmudi/)
- Powered by Tailwind CSS, Vercel deploy
- Logo, gambar, dan copywriting diupayakan mirip aslinya

---

**Silakan fork, kloning, atau request fitur baru!**  
Untuk feedback/bug, langsung open issue atau DM via [GitHub Pages](https://wahyu043.github.io/wahyumahmudi/).

Hasil demo live bisa klik disini : [pangsitgorengtmg.vercel.app](https://pangsitgorengtmg.vercel.app/)
---