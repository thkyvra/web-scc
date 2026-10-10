# Panduan Membagikan Halaman HTML

Halaman ini bisa dibuka langsung di browser, tetapi untuk dibagikan ke orang lain, ada dua cara yang umum dipakai:

## 1. Jalankan di komputer lokal

Buka terminal di folder project ini, lalu jalankan:

```bash
cd /Users/wahyuniarif/Downloads/web-scc-html
python3 -m http.server 8000
```

Setelah itu buka browser dan akses:

```text
http://localhost:8000
```

Ini cocok untuk preview di komputer yang sama.

## 2. Bagikan ke orang lain

Agar orang lain bisa membuka halaman, halaman harus diupload ke hosting web atau GitHub Pages.

### Cara paling sederhana

1. Upload folder ini ke GitHub.
2. Buka repository di GitHub.
3. Masuk ke menu Settings > Pages.
4. Pilih branch utama dan folder root.
5. Simpan.
6. GitHub akan memberi link seperti:

```text
https://username.github.io/nama-repository/
```

Link inilah yang kemudian bisa dikirim ke orang lain.

## 3. Cara copy link halaman

Di browser:

- Klik kolom alamat di bagian atas
- Tekan Ctrl + C (Windows/Linux) atau Command + C (macOS)
- Link langsung tersalin ke clipboard
- Paste dengan Ctrl + V / Command + V di chat, email, atau WhatsApp

## 4. Kalau ingin langsung bisa dibuka di browser

Jalankan file HTML secara langsung juga bisa, tapi link yang dihasilkan biasanya seperti:

```text
file:///Users/.../index.html
```

Link itu hanya bisa dipakai pada komputer yang sama.

## 5. Script cepat

Untuk memudahkan, file `serve.sh` sudah dibuat. Jalankan:

```bash
./serve.sh
```

Lalu buka:

```text
http://localhost:8000
```
