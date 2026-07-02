# README – Database Perikanan (Stored Procedure)

## Deskripsi Proyek

Database **Perikanan** merupakan sistem basis data yang dirancang untuk membantu pengelolaan data pada usaha perikanan. Database ini digunakan untuk menyimpan informasi mengenai data ikan, kolam, stok, pakan, hasil tangkapan, dan penjualan. Selain itu, database ini memanfaatkan **Stored Procedure** untuk mempermudah proses pengolahan data seperti menampilkan, menambah, mengubah, menghapus, mencari, dan melakukan backup data.

---

# Tujuan

Tujuan pembuatan database ini adalah:

* Mengelola data perikanan secara terstruktur.
* Mempermudah proses pengolahan data menggunakan MySQL/MariaDB.
* Mengurangi penulisan query yang berulang melalui Stored Procedure.
* Menjaga keamanan dan konsistensi data.
* Mempermudah proses pencadangan (backup) data.

---

# Software yang Digunakan

* XAMPP
* MariaDB / MySQL
* phpMyAdmin (Opsional)
* Visual Studio Code (Opsional)

---

# Nama Database

```sql
perikanan
```

---

# Struktur Tabel

Database terdiri dari beberapa tabel utama, yaitu:

1. ikan
2. kolam
3. kolam_backup
4. stok
5. pakan
6. hasil_tangkapan
7. penjualan

Selain tabel tersebut terdapat beberapa View:

* view_ikan
* view_harga_tinggi
* view_harga_tertinggi
* view_harga_diatas_rata

---

# Stored Procedure

## 1. P_TAMPIL_IKAN

### Fungsi

Menampilkan seluruh data ikan.

### Cara Menjalankan
## 2. P_TAMBAH_IKAN
### Fungsi
Menambahkan data ikan baru.
### Cara Menjalankan
## 3. P_UPDATE_IKAN
### Fungsi
Mengubah data ikan berdasarkan ID.
### Cara Menjalankan
## 4. P_HAPUS_IKAN
### Fungsi
Menghapus data ikan berdasarkan ID.
## 5. P_CARI_IKAN
### Fungsi
Mencari data ikan berdasarkan nama.
### Cara Menjalankan
# Keunggulan Stored Procedure
* Mengurangi penulisan query yang berulang.
* Meningkatkan performa database.
* Mempermudah pemeliharaan sistem.
* Menjadikan kode SQL lebih rapi dan terstruktur.
* Meningkatkan keamanan karena pengguna cukup menjalankan procedure tanpa mengakses query secara langsung.
# Kesimpulan
Database **Perikanan** dengan penerapan **Stored Procedure** mampu membantu pengelolaan data secara lebih efektif dan efisien. Berbagai operasi seperti menampilkan data, menambah data, memperbarui data, menghapus data, mencari data, hingga melakukan backup dapat dilakukan dengan mudah menggunakan perintah `CALL`. Implementasi Stored Procedure juga membuat sistem lebih terstruktur, mengurangi kesalahan penulisan query, dan meningkatkan kemudahan dalam pengembangan maupun pemeliharaan aplikasi di masa mendatang.
