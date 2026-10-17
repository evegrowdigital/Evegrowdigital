# Landing page (HTML + gambar + hotspot klik)

## Struktur
```
index.html
vercel.json
images/   <- taruh gambarmu di sini
  hero.png, bukti-1..4.png, kenapa.png, cta.png, private-course.png, pilih.png
```

## Cara pasang hotspot (overlay klik)
Setiap `<a class="hotspot" style="--top:25%;--left:26%;--w:35%;--h:15%">`:
- `--top` / `--left` = posisi TITIK TENGAH tombol di gambar (%)
- `--w` / `--h` = ukuran area klik (%)
Buka `index.html?debug` untuk melihat kotak merah area klik.

## Deploy
1. Buat repo GitHub baru, upload semua file (termasuk folder images).
2. vercel.com > Add New > Project > import repo > Deploy. (Framework: Other, tanpa build command)
