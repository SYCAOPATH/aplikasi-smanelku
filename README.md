## Tentang SMANELKU

SMANELKU adalah aplikasi manajemen sekolah berbasis website yang di bangun dan di kembangkan dengan Framework Laravel. Fitur-fitur pada aplikasi SMANELKU antara lain :

- Website Sekolah (Done)
- PPDB (Done)
- Perpustakaan (Done)
- Sistem Pembayaran Sekolah SPP (Done)
- Alumni

## Installation

* Install [Composer](https://getcomposer.org/download) and [Npm](https://nodejs.org/en/download)
* Clone the repository: ``
* Install dependencies: `composer install ; npm install ; npm run dev`
* Run `cp .env.example .env` for create .env file
* Run `php artisan migrate --seed` for migration database
* Run `php artisan storage:link` for create folder storage

## Penggunaan
* Login sebagai Admin email: kepsek@sch.id & pw: Bismillah
* Login sebagai PPDB, Perpustakaan, Staf, Pengajar semua dengan password 12345678

## Package
- [IndoBank](https://github.com/andes2912/indobank) package Laravel untuk menyimpan data Nama Bank yang ada di Indonesia

Note : Aplikasi ini akan terus saya update.<br>
Jika ada pertanyaan bisa kontak aku di email ini <b>ztronzs0000@gmail.com</b>
</p>


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Instalasi V.2

1. Lakukan cloning atau download source codenya, kemudian ekstrak data zipnya..
```
https://github.com/SYCAOPATH/
```
2. Install dependensi yang dibutuhkan (supaya ada vendor)
```
composer install
```
or
```
composer update
```
```
npm install
```
npm run dev
```
apabila mengalami masalah lakukan 
```
npm audit fix / npm audit fix --force
```
3. Copy `.env.example` dan rename menjadi `.env`
4. Generate app key
```
php artisan key:generate
```
5. Nyalakan server MYSQL dan Apache (XAMPP, MAMP, dll), Lalu buat database di phpMyadmin
6. Ubah isi `DB_DATABASE` pada `.env` dengan nama database yang dibuat
7. Lalu jalankan migrasi dan seeder
```
php artisan migrate --seed
```
8. Jalankan server
```
php artisan serve
```
9. Buka url dibawah menggunakan browser (Chrome, Edge, FireFox, Opera, dll)
```
http://127.0.0.1:8000 / localhost:8000
```