<img src="https://static.s-cart.org/guide/info/s-cart-content.jpg">

## <b>S-cart</b>

OSS (Open Source Software) yang dipilih untuk dilakukan penambahan fitur atau modifikasi yaitu S-cart. S-cart merupakan aplikasi berbasis web yang menggunakan framework PHP yaitu Laravel dan framework CSS yaitu Bootstrap. S-Cart adalah proyek situs web e-niaga gratis untuk individu dan bisnis. S-cart ini dibangun di atas framework (kerangka kerja) Laravel dan teknologi terbaru. Tujuan dari dibuatnya S-Cart ini adalah "Efisien dan ramah untuk semua orang".

<img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/frontend/landingpage1.png">
Tampilan Landing Page Awal S-Cart yang sudah dimodifikasi
<br>

<img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/frontend/login.png">
Tampilan halaman login sc_admin yang sudah dimodifikasi
<br>

## <b>Link Ke Repositori GIT</b>

<pre>
1. S-cart sebelum modifikasi: <a href="https://github.com/s-cart/s-cart">https://github.com/s-cart/s-cart</a>
2. S-cart setelah modifikasi: <a href="https://git.stis.ac.id/riofeb/s-cart">https://git.stis.ac.id/riofeb/s-cart</a>
</pre>

## <b>KELOMPOK 6</b>

- Riofebri Prasetya / (221911192) - Ketua
- Dwi Joko Purnomo / (221910685)
- I Wayan Chandra Purwatmaja / (221910870)
- Maulyta Noer Fadilla / (221910938)
- Denisa Hilmy Atiqah / (221911050)

## <b>Deskripsi Singkat S-cart</b>

> Deskripsi

```
S-cart merupakan aplikasi berbasis web yang menggunakan framework PHP yaitu Laravel dan framework CSS yaitu Bootstrap. S-Cart adalah proyek situs web e-commerce gratis untuk individu dan bisnis. S-cart ini dibangun di atas framework (kerangka kerja) Laravel dan teknologi terbaru. Tujuan dari dibuatnya S-Cart ini adalah "Efisien dan ramah untuk semua orang". S-cart memiliki menu untuk Admin dan untuk Customer atau user
```

<img src="https://s-cart.org/data/30/shop-list.jpg?v=1">
<img src="https://s-cart.org/data/30/admin-dashboard.jpg?v=1">

sumber: <a href="https://s-cart.org/">https://s-cart.org/</a>

## <b>Requirements:</b>

```
- PHP >= ^7.3|^8.0 (S-Cart 6.x)
- PHP >= ^8.0.2 (S-Cart 7.x)
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Ctype PHP Extension
- JSON PHP Extension
- BCMath PHP Extension
```

## <b>Daftar perubahan</b>

1. Modifikasi fitur Register (Frontend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_1.png">
   <br>

2. Modifikasi fitur Change Information (Frontend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_2.png">
   <br>

3. Modifikasi fitur Store Config Costumer (Backend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_3.png">
   <br>

4. Modifikasi fitur Home dengan menambahkan konten berita (Frontend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_4.png">
   <br>

5. Modifikasi button LOGIN dan REGISTER menjadi satu dropdown (Frontend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_5.png">
   <br>

6. Modifikasi tata letak dan desain halaman CONTACT US
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_6.png">
   <br>

7. Modifikasi Penambahan fitur bahasa Indonesia
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_7.png">

8. Modifikasi sidebar (Backend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_8.jpeg">
   <br>

9. Modifikasi desain tema (Backend)
   <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_9.jpeg">
   <br>

10. Modifikasi penambahan fitur captcha di Sc_Admin (Backend)
    <img src="https://raw.githubusercontent.com/rii92/laporan_ppl_kelompok6/main/assets/images/fitur_10.jpeg">
    <br>

## <b>Pembagian tugas dalam kelompok</b>

1. Riofebri Prasetya:

- Hosting
- mengerjakan fitur nomor 1 sampai 4 (perancangan, implementasi)

2. Dwi Joko Purnomo

- mengerjakan fitur nomor 1 sampai 4 (perancangan, implementasi)

3. I Wayan Chandra Purwatmaja:

- mengerjakan fitur nomor 10 sampai 4 (perancangan, implementasi)

4. Maulyta Noer Fadilla:

- mengerjakan fitur nomor 5 sampai 6 (perancangan, implementasi)

5. Denisa Hilmy Atiqah:

- mengerjakan fitur nomor 1 sampai 4 (perancangan, implementasi)

## <b>Installation & configuration:</b>

<b>How to map your domain to s-cart? <a href="https://s-cart.org/en/docs/master/installation.html">CLICK HERE</a></b>

**Step1: Install last version S-cart**

Option 1: **From composer**

```
composer create-project s-cart/s-cart
```

Option 2: **From github**

```
git clone https://github.com/s-cart/s-cart.git
```

Then, install vendor:

```
composer install
```

**Step2: Set writable permissions for the following directories:**

- <code>storage</code>
- <code>vendor</code>
- <code>public/data</code>
- <code>bootstrap/cache</code>
- <code>app/Plugins</code>

**Step3: Create database**

```
- Create a new database. Example database name is "s-cart"
```

**Step4: Install**

Option 1: **Install automatic**

```
Access your-domain.com/install.php to install S-cart.
```

Then, remove or rename file _public/install.php_

Option 2: **Manual installation**

If installing with link "install.php" unsuccessful, you can install it manually below.

```
1: Create new database, then import file /vendor/s-cart/core/src/DB/s-cart-yyyy-mm-dd.sql to database.
2: Rename or delete file public/install.php
3: Copy file .env.example to .env if file .env not exist.
4: Generate API key if APP_KEY is null.
- Use command "php artisan key:generate"
5: Generates the encryption keys
  Use command "php artisan passport:keys"
6: Config value of file .env:
- APP_DEBUG=false (Set "false" is security)
- DB_HOST=127.0.0.1 (Database host)
- DB_PORT=3306 (Database port)
- DB_DATABASE=s-cart (Database name)
- DB_USERNAME=root (User name use database)
- DB_PASSWORD= (Password connect to database)
- APP_URL=http://localhost (Your url)
- ADMIN_PREFIX=sc_admin (Path to admin)
- DB_PREFIX=sc_ (Must be "sc_" because it is fixed in the .sql file)
```

**Step5: Install completed**

- Access to url admin: <b>your-domain/sc_admin</b>.
- User/pass <code><b>admin</b>/<b>admin</b></code>

More detail for installation: <a href="https://s-cart.org/en/docs/master/installation.html">HERE</a>

## <b>Useful information:</b>

To view S-Cart version information

`php artisan sc:info`

To update the core version of S-Cart:

`composer update s-cart/core`

Or you can use `php composer.phar update s-cart/core` if you don't have composer installed.

To create a plugin:

`php artisan sc:make plugin --name=Group\PluginName`

Detail: <a href="https://s-cart.org/en/docs/master/how-to-install-module-extension.html">HERE</a>

Library of free plugins for S-Cart: <a href="https://s-cart.org/en/plugin.html">HERE</a>

To create data backup file (The sql file is stored in storage/backups):

`php artisan sc:backup --path=abc.sql`

To recover data:

`php artisan sc:restore --path=abc.sql`

To manually customize the admin page (<code>resources/views/admin + config/admin.php</code>):

`php artisan sc:customize admin`

This command will create new directories `resources/views/admin` and file `config/admin.php`
After set the value `customize=true` in `config/admin.php` you can modify template admin.

To manually customize file config validation (<code>config/validation.php</code>):

`php artisan sc:customize validation`

More detail: https://s-cart.org/en/docs/master
