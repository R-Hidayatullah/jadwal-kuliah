# Jadwal Kuliah

Ini adalah aplikasi sederhana untuk menampilkan jadwal kuliah dari website [SIA UMPWR](http://sia.umpwr.ac.id/index.php). Aplikasi ini menggunakan HTML dan JavaScript untuk membaca data dari file teks dan menampilkannya dalam tabel serta grafik.

## Cara Menggunakan

1. **Menyalin Data Jadwal Kuliah**
   - Kunjungi halaman jadwal kuliah di [SIA UMPWR](http://sia.umpwr.ac.id/index.php).
   - Salin data jadwal kuliah mulai dari hari Senin hingga akhir minggu.
   - Simpan data yang telah disalin ke dalam file teks dengan nama `jadwal_kuliah.txt`. Pastikan format data sesuai dengan format yang diharapkan oleh aplikasi.

2. **Menyiapkan File**
   - Tempatkan file `jadwal_kuliah.txt` dan `index.html` dalam direktori yang sama.

3. **Menjalankan Aplikasi dengan Server Web Lokal**
   - **Menggunakan Python**:
     1. Pastikan Python terinstal di sistem Anda.
     2. Buka terminal atau command prompt dan navigasikan ke direktori yang berisi file `index.html` dan `jadwal_kuliah.txt`.
     3. Jalankan perintah berikut untuk memulai server web lokal:
        ```bash
        python -m http.server 8000
        ```
     4. Buka browser web dan kunjungi `http://localhost:8000/` untuk melihat aplikasi.

4. **Menampilkan Data**
   - Aplikasi akan memuat dan menampilkan jadwal kuliah dalam bentuk tabel.
   - Selain itu, aplikasi juga akan menghasilkan grafik yang menunjukkan jumlah mahasiswa untuk setiap mata kuliah.

## Struktur File

- **`index.html`**: File HTML yang berisi kode untuk menampilkan jadwal kuliah.
- **`jadwal_kuliah.txt`**: File teks yang berisi data jadwal kuliah yang disalin dari website.

Pastikan bahwa file `jadwal_kuliah.txt` diupdate sesuai dengan jadwal kuliah terbaru untuk memastikan informasi yang ditampilkan selalu akurat.
