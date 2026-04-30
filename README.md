# Student Laravel - Aplikasi Tolongin

## Deskripsi Aplikasi
**Tolongin** adalah aplikasi web berbasis Laravel yang dirancang untuk memudahkan pengguna dalam mencari dan mengelola berbagai layanan jasa (seperti cleaning, repair, laundry, dll).

Project ini merupakan tugas individu mahasiswa untuk mengimplementasikan fitur **CRUD** menggunakan framework Laravel.

## Fitur yang Telah Diimplementasikan
- CRUD Lengkap Mahasiswa/Layanan
- Tampilan data dengan tabel
- Form input data
- Edit dan hapus data
- Routing dan Controller MVC
- Migration dan Seeder Database

## Tech Stack
- **Backend**: Laravel (PHP Framework)
- **PHP**: 8.2 / 8.3
- **Database**: MySQL
- **Frontend**: Blade Template + Bootstrap
- **Lainnya**: Composer, Vite, Git & GitHub

## Cara Menjalankan Aplikasi

```bash
# 1. Masuk ke folder project
cd C:\xampp\htdocs\Student-laravel

# 2. Install dependencies
composer install

# 3. Copy file environment
copy .env.example .env

# 4. Generate application key
php artisan key:generate

# 5. Buat database dan jalankan migration
php artisan migrate

# 6. Jalankan server
php artisan serve