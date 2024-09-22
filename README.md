# Aplikasi GUI pada CRUD dengan Java Swing dan JDBC
Membuat aplikasi GUI dengan CRUD menggunakan Java Swing dan JDBC

---
## 🗂️ Table Of Contents
- [Koneksi Database dengan JDBC](https://github.com/adeliafhr/Tugas-Pertemuan-Kelima/blob/main/Barang.java)
- [DbUtils](https://github.com/adeliafhr/Tugas-Pertemuan-Kelima/blob/main/DbUtils.java)
- [Java Swing](https://github.com/adeliafhr/Tugas-Pertemuan-Kelima/blob/main/Barang.java)
- [Penerapan CRUD](https://github.com/adeliafhr/Tugas-Pertemuan-Kelima/blob/main/Barang.java)
---
## 🌐 Koneksi Database dengan JDBC
JDBC atau Java Database Connection digunakan untuk menghubungkan aplikasi dengan database.
### Langkah - Langkah untuk Menghubungkan :
1. Menambahkan driver JDBC yang sesuai dan membuat objek Connection menggunakan DriverManager.
2. Setelah terhubung, buat object statement dan preparedStatement untuk menjalankan pernyataan SQL
3. Tulis nama driver JDBC yang digunakan untuk menghubungkan aplikasi dengan database PostgreSQL.
4. Tulis database yang sudah di buat pada PostgreSQL
5. Tulis user dan password yang di gunakan pada database

---
## ⚙️ Db Utils 
Db Utils atau Database Utilities digunakan untuk mengonversi hasil query dari database (ResultSet) menjadi model tabel yang ditampilkan pada *JTable* 
### Langkah - Langkah : 
1. Input paramater yaitu ResutlSet yang berisi data yang diambil dari database
2. Ambil MetaData kolom menggunakan ResultSetMetaData
3. Buat vector untuk menyimpan nama - nama kolom dari metadata
4. Buat vector baru untuk menyimpan semua baris data
5. Kembalikan object DefaultTableModel yang berisi data baris dan nama kolom
---
## 🖥️ Java Swing
Java Swing adalah sekumpulan kode yang digunakan untuk mengembangkan aplikasi desktop dengan antarmuka grafis yang responsif dan interaktif.
### Komponen GUI
- JTable : menampilkan data dalam bentuk tabel
- JButton : melakukan aktivitas ketika di klik oleh pengguna
- JLabel : menampilkan teks yang tetap
- JTextField : tempat untuk menulis teks
---
## 📊 Penerapan CRUD 
Berikut adalah penjelasan penerapan CRUD pada GUI
### 1. Create (tambah)
Penambahan data dilakukan pada tabel Barang dimana pengguna memasukkan informasi Barang seperti ID Barang, Nama Barang, dan Harga. Setelah data ditambahkan maka akan muncul 
informasi "data berhasil ditambahkan". Semua data yang sudah di input akan tersimpan aman menggunakan perintah commit. 
### 2. Read (tampil)
Perintah tampil data berfungsi untuk menampilkan semua data pada tabel. Ketika pengguna memilih satu data pada tabel maka data otomatis akan tampil pada text filed yang ada pada tabel
sesuai dengan informasi yang di masukkan.
### 3. Update (mengubah)
Pengubahan data dilakukan pada tabel Barang dimana pengguna dapat memilih ID Barang yang akan di ubah kemudian menulis informasi yang diubah seperti nama barang dan harga. Setelah perubahan berhasil maka akan muncul informasi "data berhasil diupdate" dan data dapat dilihat pada tabel.
### 4. Delete (menghapus)
Penghapusan data dilakukan pada tabel Barang dimana pengguna memilih data pada tabel yang akan di hapus, jika data berhasil di hapus maka akan muncul informasi "data berhasil dihapus" kemudian pengguna dapat melihat data pada tabel apakah data sudah terhapus atau belum.

---
## 📝 Kesimpulan
Aplikasi CRUD dengan Java Swing dan JDBC adalah solusi yang baik untuk operasi dasar pada database yaitu Create, Read, Update, dan Delete. Java Swing membantu dalam tampilan yang menarik sementara JDBC memastikan java terhubung dengan database.

---
**📖Semoga README ini membantu dalam memahami dan menggunakan Java Swing untuk pengembangan aplikasi GUI!💡**
