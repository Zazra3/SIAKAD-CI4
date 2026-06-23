# SIAKAD - Sistem Informasi Akademik

SIAKAD adalah aplikasi sistem informasi akademik berbasis web yang dibangun menggunakan **CodeIgniter 4.x** dan **FakerPHP** (untuk generator data dummy pada testing).

## Fitur Utama
- Sistem Autentikasi (Login/Logout)
- Dashboard Statistik Akademik
- Manajemen Data Mahasiswa (CRUD & Detail)
- Manajemen Data Dosen (CRUD & Detail)
- Manajemen Data Program Studi (Prodi)
- Laporan Akademik & Pengaturan Sistem

## Persyaratan Sistem
- PHP >= 8.1 (Direkomendasikan)
- MySQL / MariaDB
- Composer (untuk manajemen vendor/dependensi)

## Langkah Instalasi

1. **Clone Repositori**
   Ekstrak file atau clone repositori ini ke direktori server lokal Anda (misal: `htdocs` atau `var/www/html`).

2. **Instalasi Dependensi Vendor**
   Buka terminal di dalam folder proyek `siakad/` dan jalankan perintah:
```bash
   composer install
cp env .env

   database.default.hostname = localhost
   database.default.database = nama_database_anda
   database.default.username = root
   database.default.password = 
   database.default.DBDriver = MySQLi
