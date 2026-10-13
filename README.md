# Layanan Pengaduan MPP Alaya Sewagati Kota Tegal

Paket frontend untuk hosting statis menggunakan GitHub Pages. Logo telah dipisahkan dari HTML dan disimpan di folder `assets`.

## Struktur folder

```text
 alaya-sewagati-github-pages/
 ├── index.html
 ├── README.md
 └── assets/
     └── logo-alaya-sewagati.png
```

## Hosting melalui GitHub Pages

1. Ekstrak file ZIP paket ini.
2. Unggah `index.html`, `README.md`, dan folder `assets` ke direktori utama repository GitHub (branch `main`).
3. Buka **Settings → Pages** pada repository.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu deployment selesai dan buka URL GitHub Pages yang ditampilkan GitHub.

## Catatan

- Jangan memindahkan `index.html` tanpa ikut memindahkan folder `assets`; jalur logo dan favicon menggunakan path relatif `assets/logo-alaya-sewagati.png`.
- GitHub Pages hanya meng-host frontend statis. Fitur yang membaca/menulis data, autentikasi, notifikasi, atau fungsi lain yang bergantung pada backend tetap memerlukan layanan backend/API yang dikonfigurasi di dalam aplikasi.
- Paket ini mempertahankan kode aplikasi dari file HTML sumber dan hanya memisahkan gambar yang tertanam menjadi file aset terpisah.
