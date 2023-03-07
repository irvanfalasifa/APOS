

<h1 align='center'>
  Hi, I'm Irvan Falasifa
</h1>

<p align='center'>
  APOS contoh aplikasi point of sales with Laravel
</p>

<p align='center'>
 <a href='mailto:irvan.falasfia@gmail.com'> 
  <img src="https://img.shields.io/badge/mail%20box-EA4335?style=for-the-badge&logo=Gmail&logoColor=white" /> 
 </a>&nbsp;&nbsp;
  
</p>

## Tentang Aplikasi

Aplikasi POS atau point of sales adalah aplikasi yang digunakan untuk mengelola transaksi pada sebuah toko atau oleh kasir. Aplikasi ini dibuat menggunakan Laravel v8.* dan minimal PHP v7.4 jadi apabila pada saat proses instalasi atau penggunaan terdapat error atau bug kemungkinan karena versi dari PHP yang tidak support.

### Beberapa Fitur yang tersedia:
- Manajemen Kategori Produk
- Manajemen Produk
  - Multiple Delete
  - Cetak Barcode
- Manajemen Member atau Anggota
  - Cetak Kartu Member
- Manajemen Supplier
- Transaksi Pengeluaran
- Transaksi Pembelian
- Transaksi Penjualan
- Laporan Pendapatan atau Laba & Rugi
  - Bulanan
  - Harian
  - Custom Tanggal
- Custom Tipe Nota
  - Nota Besar
  - Nota Kecil / Thermal Nota
- Manajemen User dan Profil
- Pengaturan Toko
  - Identitas
  - Upload Desain Kartu Member
  - Setting Diskon Member
- User (Administrator, Kasir)
- Grafik ChartJS pada Dashboard

## Instalasi
#### Via Git
```bash
git clone https://github.com/irvanfalasifa/APOS.git
```

### Setup Aplikasi
Jalankan perintah 
```bash
composer update
```
atau:
```bash
composer install
```
Copy file .env dari .env.example
```bash
cp .env.example .env
```
Konfigurasi file .env
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example_app
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:QGRW4K7UVzS2M5HE2ZCLlUuiCtOIzRSfb38iWApkphE=
APP_DEBUG=true
APP_URL=http://example-app.test
```
Generate key
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate
```
Seeder table User, Pengaturan
```bash
php artisan db:seed
```
Menjalankan aplikasi
```bash
php artisan serve
```

## License

[MIT license](https://opensource.org/licenses/MIT)
