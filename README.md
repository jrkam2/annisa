# Dashboard AEON EJI (versi web)

Situs statis: tidak perlu build, tidak perlu install apa pun.

## Isi
- `index.html` – aplikasi dashboard
- `data/seed.json` – data sales CSR AEON, HET, BA & target
- `data/packs.json` – foto produk (packshot)
- `img/annisa.webp` – memoji header
- `vercel.json` – pengaturan Vercel (noindex, cache)

## Deploy ke Vercel
1. Buat repository baru di GitHub (boleh **Private**), lalu klik **uploading an existing file** dan seret semua isi folder ini (termasuk folder `data` dan `img`). Klik **Commit changes**.
2. Di Vercel, tempel URL repository GitHub tadi di kotak "Ask v0 to build or enter a Git repository URL", lalu **Import**.
3. Framework Preset: **Other**. Build Command dan Output Directory dikosongkan. Klik **Deploy**.

## Update data
Ganti `data/seed.json` di GitHub (Add file → Upload files → Commit). Vercel otomatis deploy ulang dalam ±1 menit.
