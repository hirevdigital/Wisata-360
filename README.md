# Jelajah Wisata 360° — website gratis

## Cara memasang foto
1. Siapkan foto panorama equirectangular JPG 360° (rasio 2:1).
2. Simpan di folder `images/` dengan nama `gerbang.jpg`, `taman.jpg`, dan `puncak.jpg`.
3. Ubah nama lokasi, deskripsi, file gambar, dan hotspot pada array `LOCATIONS` di `script.js`.
4. `pitch` dan `yaw` menentukan posisi hotspot dalam derajat; sesuaikan dengan arah pintu/jalan pada panorama masing-masing.

## Cara preview
Buka `index.html` pada browser, atau jalankan server lokal `python -m http.server 8000` dan buka http://localhost:8000. Untuk pemakaian online, deploy ke GitHub Pages.

## Deploy GitHub Pages
1. Buat akun GitHub di github.com.
2. Buat repository baru, misalnya `wisata360`, dan atur **Public**.
3. Pilih Add file > Upload files; unggah `index.html`, `style.css`, `script.js`, dan folder `images` beserta foto.
4. Commit changes.
5. Buka Settings > Pages > Build and deployment > Deploy from a branch.
6. Pilih branch `main`, folder `/(root)`, lalu Save.
7. Tunggu deployment; akses https://USERNAME.github.io/wisata360/.

Catatan: Pannellum dimuat dari CDN; koneksi internet diperlukan. Foto panorama contoh dari situs Pannellum dipakai bila file lokal belum tersedia. Untuk hasil terbaik unggah semua foto sendiri.
