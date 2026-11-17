# Laporan mingguan portofolio saham

- `index.html` halaman ringkas untuk pemilik dana, dibuka di HP. Membaca `data/ringkas.json` (teks awam per minggu) dan `data/paket.json` (grafik).
- `rinci.html` versi lengkap, membaca `data/paket.json`.
- Draf minggu baru ditaruh di `data/ringkas-draft.json` dan `data/draft.json`, dilihat lewat `?draft`. Setelah dicek, keduanya disalin menjadi `ringkas.json` dan `paket.json`.
