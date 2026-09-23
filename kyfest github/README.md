# KYFEST 2026 — GitHub Hosting Package

Paket ini sudah dirapikan dari file landing page KYFEST 2026 agar lebih mudah diedit melalui GitHub.

## Struktur
- `index.html` — isi/teks halaman
- `assets/css/style.css` — warna, ukuran, font, layout, dan desain
- `assets/js/script.js` — fungsi/interaksi JavaScript
- `assets/images/` — gambar yang sebelumnya tertanam sebagai Base64

## Cara upload ke GitHub
1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini.
3. Pastikan `index.html` berada di folder utama repository.
4. Untuk GitHub Pages: buka **Settings → Pages**.
5. Pilih **Deploy from a branch**, pilih branch utama (biasanya `main`) dan folder `/ (root)`.
6. Simpan, lalu tunggu proses deployment.

## Cara edit
- Teks: buka `index.html`.
- Warna/ukuran/posisi: buka `assets/css/style.css`.
- Gambar: ganti file di `assets/images/` dengan nama file yang sama, atau ubah path-nya di HTML/CSS.
- Interaksi: buka `assets/js/script.js`.

## Catatan
Struktur visual asli dipertahankan semaksimal mungkin. Gambar Base64 dipisahkan menjadi file agar lebih mudah dikelola di GitHub.
