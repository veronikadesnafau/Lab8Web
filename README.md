# Lab8Web
Database PHP dan Mysql

###### Nama : Veronika Desna Fau
###### NIM : 312010333
###### Kelas : TI.A.2

## Tugas PHP

Instruksi Praktikum

1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab8_php_database pada docroot webserver 
(htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

Langkah-langkah Praktikum

Persiapan

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah 
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan 
melalui XAMPP.
Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![](img/1%20satu.jpg)

Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka 
melalui browser: http://localhost/phpmyadmin/

Membuat Database: Studi Kasus Data Barang

###### Membuat database

![](img/2%20buatdb.jpg)

###### Membuat table menggunaka query

![](img/3%20query.jpg)

###### Berhasil membuat table

![](img/4%20succesful.jpg)

###### Menambahkan data menggunakan query

![](img/5%20menambahkan.jpg)

###### data berhasi ditambahkan

![](img/6%20created.jpg)

###### Tampilan table

![](img/7%20created.jpg)

###### Membuat Program CRUD

Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![](img/8%20htdocs.jpg)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: 
http://localhost/lab8_php_database/

![](img/9%20chrome.jpg)

###### Membuat file koneksi database

Buat file baru dengan nama koneksi.php

![](img/10%20koneksi.jpg)

Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan 
koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”; 

![](img/10%20koneksichrome.jpg)

###### Membuat file index untuk menampilkan data (Read)

Buat file baru dengan nama index.php

![](img/11%20vsc.jpg)

![](img/12%20vsc.jpg)

hasil :

![](img/13%20hasil.jpg)

###### Menambah Data (Create)

Buat file baru dengan nama tambah.php

![](img/14%20a.jpg)

![](img/14%20b.jpg)

Hasil :

![](img/14%20tambah.jpg)

###### Mengubah Data (Update)

Buat file baru dengan nama ubah.php

![](img/15%20ubahdata.jpg)

![](img/15%20ubahdata2.jpg)

![](img/15%20ubahdata3.jpg)

![](img/15%20ubahdata4.jpg)

Hasil :

![](img/15%20ubahdata5.jpg)

###### Menghapus Data (Delete)

Buat file baru dengan nama hapus.php

![](img/16%20hapusdata5.jpg)

###### Tugas selesai

#### Hasil program pada browser :

![](img/index%20php1.jpg)

#### Penambahan CSS Style pada tambah.php

![](img/tambah%20barang1.jpg)

#### Penambahan CSS Style pada ubah.php
![](img/ubah%20barang%20barang1.jpg)

###### selesai



