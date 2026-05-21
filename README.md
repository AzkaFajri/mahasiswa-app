# Mahasiswa App

Aplikasi sederhana untuk mengelola data mahasiswa.

## Fitur
- Lihat daftar mahasiswa
- Tambah mahasiswa
- Edit mahasiswa
- Hapus mahasiswa

## Teknologi
- Laravel 10
- PHP 8
- MySQL

## Cara Install
```bash
git clone https://github.com/AzkaFajri/mahasiswa-app.git
cd mahasiswa-app
composer install
cp .env.example .env
php artisan key:generate
php artisan serve
