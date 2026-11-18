# WARKOP GEN Z — Website Statis Siap GitHub Pages

Website bisnis kuliner modern **WARKOP GEN Z** (*Tempat Nongkrong, Ngopi, dan Cerita Tanpa Batas*) dengan struktur minimalis dan bersih yang siap di-upload langsung ke **GitHub Pages**.

---

## Struktur Folder Repository

```text
├── img/          # Seluruh aset logo dan gambar menu makanan/minuman
├── README.md     # Panduan instalasi, deployment GitHub Pages & konfigurasi Supabase
├── index.html    # Halaman utama pengunjung, Dashboard Admin (11 Menu), dan POS Kasir
└── style.css     # Stylesheet utama (Tema Hitam, Cream, Cokelat Kopi, Orange)
```

---

## Cara Deploy ke GitHub Pages

1. Buka repository GitHub Anda, lalu upload folder **`img`**, **`README.md`**, **`index.html`**, dan **`style.css`** ke branch `main` (root repository).
2. Masuk ke menu **Settings → Pages**.
3. Pada bagian **Build and deployment**, pilih **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu 1–2 menit, website Anda langsung aktif di alamat `https://USERNAME.github.io/NAMA-REPO/`.

---

## Informasi Login & Penyimpanan Data

- **Kredensial Bawaan (Bisa Diedit Admin di menu 9. Manajemen Kasir)**:
  - **Admin**: username `admin` | sandi `123`
  - **Kasir**: username `kasir` | sandi `123`
- **Mode Demo Lokal vs. Supabase**:
  - Secara bawaan, aplikasi berjalan dalam **Mode Demo Lokal** menggunakan penyimpanan browser sehingga langsung bisa dicoba di GitHub Pages tanpa pengaturan server tambahan.
  - Untuk sinkronisasi lintas perangkat secara real-time dengan **Row Level Security (RLS)**, buka file `index.html`, cari bagian `SUPABASE_CONFIG`, lalu isi `url` dan `anonKey` dari project Supabase Anda (jangan pernah memasukkan `service_role` key ke frontend).

---

**Created by : NUR SARIFUDIN**  
Alamat: Jl. Kemandoran No.119, RT.004/RW.023, Pekayon Jaya, Kec. Bekasi Selatan, Kota Bekasi, Jawa Barat 17148.
