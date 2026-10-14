# Kartu Ulang Tahun GORO

Situs statis (HTML + CSS + JavaScript murni), tanpa build.

## Deploy ke Vercel
- **Cara cepat:** buka vercel.com/new, pilih upload/drag-and-drop folder ini, lalu Deploy.
- **Lewat GitHub:** push folder ini ke repo, Import di Vercel. Framework Preset: **Other**, Build Command & Output Directory dikosongkan.
- **Lewat CLI:** `npx vercel` di dalam folder ini, lalu `npx vercel --prod`.

## Struktur
- `index.html`: aplikasi lengkap
- `bg/1.png` sampai `bg/5.png`: background 5 varian (1080×1080)

## Coba di lokal
Jalankan `npx serve .` di folder ini (jangan buka index.html langsung via file://, karena background dimuat lewat fetch).
