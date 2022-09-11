# 2223-IF215007_8-pengembangan-aplikasi-web
# Proposal Proyek
## Permasalahan
Adanya kendala pada manajemen keuangan masjid terutama pada sistem pencatatan.

## Rancangan Solusi

 - Membuat suatu sistem yang dapat mengarsipkan bukti transaksi, pencatatan pemasukan dan pengeluaran keuangan suatu masjid. 
 - Sistem yang dibuat dapat menyimpan data pemasukan dan pengeluaran keuangan suatu masjid. 
 - Pemasukan dan pengeluaran keuangan masjid dapat dikategorikan oleh sistem supaya bendahara masjid dapat mengetahui jenis transaksinya.
 - Sistem dapat menampilkan laporan keuangan masjid, agar bendahara masjid dapat memantau perkembangan arus keuangan masjid.

## Use Case

 - User bendahara dapat menambah, mengubah, menghapus, mengedit, mencari dan mencetak data keuangan masjid.
 - User bendahara dapat melakukan pengarsipan data keuangan masjid.
 - User donatur dapat melakukan pendaftaran dan dikonfirmasi oleh user bendahara.
 - User bendahara dapat menghapus dan mengedit data yang telah diinput oleh user donatur.
 - User jama'ah masjid dapat melihat laporan keuangan yang terdiri atas pemasukan, pengeluaran dan saldo keuangan.

## Struktur Data

| Atribut | Tipe Data | Contoh |
|--|--|--|
| id_masjid | integer | 12345 |
| nama_masjid | string | Asy-Syifa |
| alamat_masjid | string | Gang Manisi |
| no_telp | string | 0217383921 |
| email | string | asysyifa@gmail.com |
| luas_tanah | integer | 80 |
| luas_bangunan | integer | 100 |
| tahun_berdiri | integer | 2010 |
| id_pengguna | integer | 111 |
| nama_pengguna | string | Bendahara Masjid |
| username | string | yogi1234 |
| password | string | 1234 |
| level | string | Administrator |
| id_kasMasjid | integer | 123 |
| tgl_kasMasjid | date | 10/09/2022 |
| uraian_kasMasjid | string | infaq jum'at |
| pemasukan | integer | 12000000 |
| pengeluaran | integer | 2000000 |
| jenis_kasMasjid | string | pemasukan |

## UX Wireframe
![Desktop - 1(2)](https://user-images.githubusercontent.com/113151072/189463468-9dbff655-4cce-42ec-bd0d-06554e6a790c.png)
