
# Aplikasi Penghitung Umur

Aplikasi Penghitung Umur adalah aplikasi berbasis Java Swing yang dirancang untuk menghitung umur seseorang berdasarkan tanggal lahirnya. Selain itu, aplikasi ini juga menampilkan informasi mengenai tanggal ulang tahun berikutnya.

## Identitas
- Nama : Addin Husnan Nadhari
- Npm : 2210010037
- Kelas : 5B Nonreg Banjarmasin
- 
## Fitur Utama

- **Hitung Umur**: Menghitung umur seseorang dalam tahun, bulan, dan hari berdasarkan tanggal lahir.
- **Tanggal Ulang Tahun Berikutnya**: Menentukan tanggal dan hari ulang tahun berikutnya.
- **User Interface (UI)**: Menggunakan Java Swing untuk tampilan antar muka yang interaktif dan mudah digunakan.

## Struktur Kode

- **PenghitungUmurFrame.java**: Kelas utama yang mengatur antarmuka pengguna dan event-event dari komponen UI.
  - `hitungUmurDetail`: Metode untuk menghitung umur detail seseorang dalam format "X tahun, Y bulan, Z hari".
  - `hariUlangTahunBerikutnya`: Metode untuk menghitung tanggal ulang tahun berikutnya berdasarkan tahun saat ini.
  - `btnHitungActionPerformed`: Event handler yang akan dipanggil ketika tombol "Hitung Umur" diklik, mengambil tanggal lahir yang dipilih oleh pengguna dan menampilkan umur dan tanggal ulang tahun berikutnya.
  - `btnKeluarActionPerformed`: Event handler untuk keluar dari aplikasi ketika tombol "Keluar" diklik.

## Cara Menggunakan

1. Jalankan program dengan menjalankan `PenghitungUmurFrame` melalui IDE atau command line.
2. Masukkan **Nama** pada field teks yang disediakan.
3. Pilih **Tanggal Lahir** menggunakan date picker.
4. Klik tombol **Hitung Umur** untuk menghitung umur dan menampilkan informasi tanggal ulang tahun berikutnya.
5. Jika ingin keluar dari aplikasi, klik tombol **Keluar**.

## Kebutuhan Sistem

- Java Development Kit (JDK) versi 8 atau lebih tinggi.
- Java Swing dan Toedter Calendar Library untuk elemen date picker.

## Pengaturan Lingkungan

1. Pastikan JDK sudah terpasang.
2. Tambahkan library `toedter-calendar` ke project Java untuk komponen date picker.

## Contoh Output

- Setelah memilih tanggal lahir dan mengklik "Hitung Umur", aplikasi akan menampilkan:
  - Umur dalam format **X tahun, Y bulan, Z hari**.
  - Tanggal ulang tahun berikutnya dan hari dalam seminggu.
