# Money Manager 
### _Aplikasi Pengelola Keuangan_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## Deskripsi
Aplikasi untuk mencatat pemasukan dan pengeluaran keuangan dengan fitur laporan keuangan.

## Pembukaan
Banyak individu yang tidak bisa mengelola keuangan mereka. Mereka juga kesulitan untuk memantau pengeluaran mereka, sehingga merasa uangnya habis entah kemana. Dengan aplikasi ini kita bisa melihat pemasukan dan pengeluaran uang kita agar bisa terorganisir. 

## Fitur Aplikasi
- Input pemasukan dan pengeluaran uang
- Daftar riwayat transaksi 
- Statistik transaksi
- Menghapus transaksi

## Tech
Aplikasi ini dibangun menggunakan:
- [Python] 8.11
- PySide 6 : Sebuah framework PyQt untuk pengembangan aplikasi desktop berbasis Python yang digunakan dalam projek ini untuk menciptakan antarmuka pengguna dengan aplikasi.
- Sqlite : Merupakan framework untuk pengembangan aplikasi desktop berbasis Python yang digunakan dalam projek ini untuk menciptakan antarmuka pengguna dengan aplikasi.
- Matplotlib : Matplotlib adalah library Python untuk membuat visualisasi data, seperti grafik dan plot. Pustaka ini memungkinkan pengguna untuk membuat berbagai jenis grafik, seperti garis, batang, dan sebar, dengan kontrol penuh atas desain dan penampilan visualnya. Labrary ini digunakan untuk menghasilkan grafik visualisasi data pengeluaran berdasarkan kategori, yang akan memudahkan pengguna dalam menganalisis keuangan mereka sendiri.
- [VsCode] : Visual Studio Code (VSCode) adalah software teks editor dari Microsoft yang mendukung berbagai bahasa pemrograman. Fitur-fitur utamanya termasuk sintaksis penyorotan, pemrograman linting, integrasi dengan kontrol versi seperti Git, serta dukungan untuk ekstensi yang memungkinkan pengguna menambah fungsionalitas sesuai kebutuhan. Aplikasi inilah yang kami gunakan untuk membuat aplikasi Money Manager.

## System Requirements
- Windows 10+

## Cara Installisasi
- Download file `Money Manager App.zip` lalu buka folder Run App.
- Anda akan melihat folder _internal dan MoneyManager.exe
- Jalankan aplikasi: Aplikasi bergantung pada module folder `_internal` jadi jika ingin membuka aplikasi harus lewat File Explorer. Jika tidak membuka lewat satu folder, aplikasi tidak akan berjalan.
###### Sayang nya kami belum bisa mengupload file `Money Mananger App.zip` dikarenakan ukuran file nya terlalu besar.


## Membuka melalui VsCode.
- Clone repositori: `git clone https://github.com/SatriaStarr/Project-PPV.git`
- Download file `Project UAS PPV - KELOMPOK 5.zip` install library/dependensi yang diperlukan.
- Install dependensi: Masuk ke terminal lalu ketik `pip install -r requirements.txt`

## Struktur Proyek
- `run_MainWindow.py`: Skrip utama aplikasi.
- `database.py`: Folder untuk skrip database.
- `README.md`: Dokumentasi proyek.

## Panduan 
##### _note: Aplikasi ini menggunakan Bahasa Inggris_
- Saat aplikasi berjalan, Anda akan melihat antarmuka utama yang menyediakan beberapa fitur:
1. Homepage yang berisi tabel pemasukan, pengeluaran uang dan tombol untuk melakukan transaksi.
2. Transaction List yang menampilkan data transaksi yang sudah disimpan dalam database (pemasukan atau pengeluaran).
3. View Statistic yang menampilkan grafik pemasukkan dan pengeluaran setiap bulan.

- Untuk menambahkan transaksi (baik Pemasukan atau Pengeluaran):
1. Klik tombol tambah transaksi (tombol tambah di bawah pojok kanan pada Homepage). Ini akan membuka form input.
2. Pada form input, pilih jenis transaksi yang diinginkan (Pemasukan atau Pengeluaran).
3. Isi nilai nominal transaksi di kolom yang sesuai.
4. Pilih kategori dan akun yang sesuai dari dropdown list (misalnya, kategori "Uang Saku" atau "Gaji").
5. Klik tombol Simpan untuk menyimpan transaksi ke dalam database. Jika data berhasil disimpan, akan muncul pesan Data berhasil disimpan.
6. Setelah transaksi ditambahkan, data akan muncul di tabel Daftar Transaksi. Tabel ini memuat kategori, tanggal, nominal, status (Pemasukan/Pengeluaran), dan akun dari transaksi.

- Menghapus Transaksi:
1. Pergi ke halaman Transaction List lalu pilih tabel transaksi yang ingin dihapus.
2. Klik tombol Hapus Transaksi. Aplikasi akan meminta konfirmasi sebelum menghapus data yang dipilih.
3. Setelah data dihapus, aplikasi akan memperbarui tampilan dan menghapus data tersebut dari database.

- Melihat Statistik Transaksi:
1. Di halaman Transaction List klik tombol View Statistic di pojok kanan bawah. 
2. Saat mengkliknya anda akan melihat grafik pemasukan dan pengeluaran.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [Python]: <https://www.python.org/downloads/>
   [VsCode]: <https://code.visualstudio.com/download>
   [github]: <https://github.com/SatriaStarr/Project-PPV>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
