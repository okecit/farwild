# FARWILD Website

Website profil brand FARWILD (sepatu hiking). Situs statis: HTML + CSS inline, tanpa build step.

## Struktur
- `index.html` halaman utama
- `assets/` logo, foto produk, poster
- `vercel.json` konfigurasi Vercel

## Jalankan lokal
Buka `index.html` di browser, atau jalankan `npx serve .`

## Push ke GitHub
```bash
git init
git add .
git commit -m "Initial commit: website FARWILD"
git branch -M main
git remote add origin https://github.com/USERNAME/farwild-website.git
git push -u origin main
```

## Deploy ke Vercel
1. Buka vercel.com, klik **Add New > Project**, lalu import repo GitHub ini.
2. **Framework Preset**: Other. Kosongkan Build Command dan Output Directory.
3. Klik **Deploy**.

## Yang perlu diganti sebelum rilis
- Tombol "Belanja Sekarang" mengarah ke `https://www.instagram.com/fhna.jn`. Ganti dengan link toko online atau WhatsApp jika sudah ada.
- Cek klaim produk (waterproof, ringan, tahan lama) sebelum dipublikasikan.
