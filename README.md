# WillHamz Academy

WillHamz Academy adalah platform pembelajaran pemrograman online yang bertujuan untuk menyediakan pengetahuan pemrograman secara luas dan mudah dimengerti oleh banyak orang.

## Daftar Isi
- [Tujuan Website](#tujuan-website)
- [Deskripsi Proyek](#deskripsi-proyek)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Struktur Proyek](#struktur-proyek)
- [Cara Memulai](#cara-memulai)
  - [Prasyarat](#prasyarat)
  - [Instalasi](#instalasi)
  - [Menjalankan Aplikasi](#menjalankan-aplikasi)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

## Tujuan Website

WillHamz Academy bertujuan untuk:
1. Menyediakan kursus pemrograman yang komprehensif dan mudah diakses.
2. Membantu pemula untuk memulai perjalanan mereka dalam dunia pemrograman.
3. Menyediakan sumber daya belajar yang terstruktur dan interaktif.
4. Membangun komunitas pembelajar yang saling mendukung.

## Deskripsi Proyek

WillHamz Academy adalah platform pembelajaran pemrograman online yang dibangun menggunakan teknologi modern. Proyek ini terdiri dari dua bagian utama:

1. **Frontend**: Antarmuka pengguna yang responsif dan intuitif, dibangun dengan React.
2. **API**: Backend yang kuat untuk menangani logika bisnis, autentikasi, dan integrasi database, dibangun dengan Express.js.

Platform ini menawarkan berbagai kursus pemrograman, dari tingkat pemula hingga lanjutan, dengan sistem pembayaran yang terintegrasi menggunakan Stripe.

## Teknologi yang Digunakan

- Frontend: React
- Backend: Express.js
- Database: MySQL
- Pembayaran: Stripe
- Lainnya: (tambahkan teknologi lain yang Anda gunakan)

## Struktur Proyek

Proyek ini dibagi menjadi dua folder utama:

```
willhamz-academy/
│
├── api/             # Backend Express.js
│   ├── src/
│   ├── package.json
│   └── ...
│
└── frontend/        # Frontend React
    ├── src/
    ├── public/
    ├── package.json
    └── ...
```

## Cara Memulai

### Prasyarat

- Node.js (versi 14 atau lebih baru)
- MySQL
- NPM atau Yarn

### Instalasi

1. Clone repositori:
   ```
   git clone https://github.com/your-username/willhamz-academy.git
   cd willhamz-academy
   ```

2. Install dependensi untuk backend:
   ```
   cd api
   npm install
   ```

3. Install dependensi untuk frontend:
   ```
   cd ../frontend
   npm install
   ```

4. Atur variabel lingkungan:
   - Buat file `.env` di folder `api` dan `frontend`
   - Isi dengan konfigurasi yang diperlukan (contoh: DATABASE_URL, STRIPE_KEY, dll.)

### Menjalankan Aplikasi

1. Jalankan backend:
   ```
   cd api
   npm start
   ```

2. Dalam terminal terpisah, jalankan frontend:
   ```
   cd frontend
   npm start
   ```

3. Buka browser dan akses `http://localhost:3000`

## Kontribusi

Kami sangat menghargai kontribusi dari komunitas. Jika Anda ingin berkontribusi, silakan buat pull request atau buka issue untuk diskusi fitur baru atau perbaikan bug.

## Lisensi

[MIT License](LICENSE)
