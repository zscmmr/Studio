# zscmmr Portfolio

Portfolio landing page dan portfolio utama yang dibuat sebagai website statis untuk GitHub Pages.

## Fitur

- Halaman utama portfolio link hub
- Halaman portfolio utama dengan deskripsi layanan
- Halaman contoh website yang dibuka ke project lain
- Optimasi aset gambar ke format WebP via script Node.js
- Siap dipublish ke GitHub Pages

## Menjalankan lokal

```bash
npm install
npm run build
python -m http.server 8000
```

Lalu buka http://localhost:8000

## Deploy ke GitHub Pages

1. Push project ke repository GitHub.
2. Buka Settings > Pages.
3. Pilih Source: GitHub Actions.
4. Workflow deployment sudah tersedia di `.github/workflows/deploy-pages.yml`.

## Struktur utama

- `index.html` — halaman utama link hub
- `portfolio-utama.html` — portfolio utama
- `website-example.html` — halaman contoh website
- `assets/` — file CSS, JS, dan gambar hasil optimize
- `scripts/optimize-images.js` — script optimasi gambar

## Catatan

Project ini menggunakan HTML statis tanpa framework, cocok untuk deployment di GitHub Pages.
