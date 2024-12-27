# Deskripsi Program Validasi Input Pendaftaran Online

Program ini dirancang untuk memvalidasi input data yang diperlukan dalam aplikasi pendaftaran online. Terdapat tiga jenis data yang akan divalidasi, yaitu:

## 1. Nama Lengkap
- **Kriteria Validasi**: Nama lengkap harus hanya berisi huruf.
- **Metode Validasi**: Menggunakan metode `isalpha()` untuk memeriksa apakah semua karakter dalam nama merupakan huruf.

## 2. Nomor Telepon
- **Kriteria Validasi**: Nomor telepon harus hanya berisi angka.
- **Metode Validasi**: Menggunakan metode `isdigit()` untuk memastikan bahwa semua karakter dalam nomor telepon adalah digit.

## 3. Email
- **Kriteria Validasi**: Email harus mengandung karakter `@` dan setidaknya satu karakter `.` setelah karakter `@`.
- **Metode Validasi**: Memeriksa keberadaan karakter `@` dan memastikan bahwa ada karakter `.` di bagian domain email setelah `@`.

## Pesan Hasil Validasi
- Jika semua data yang dimasukkan valid, program akan menampilkan pesan:
  *data pendaftar valid*
  - Jika ada kesalahan dalam salah satu input, program akan menampilkan pesan error yang sesuai untuk setiap kesalahan yang terdeteksi.

## Contoh Penggunaan
Program akan meminta pengguna untuk memasukkan:
- Nama lengkap
- Nomor telepon
- Email

Setelah menerima input, program akan melakukan validasi dan memberikan umpan balik berdasarkan hasil validasi tersebut.

## Contoh Kode
Berikut adalah contoh kode Python yang digunakan untuk melakukan validasi input:

![perintah 1](https://github.com/user-attachments/assets/403b54eb-6565-496f-b2b8-4ec290c4c84e)
![perintah 2](https://github.com/user-attachments/assets/9d56c3f8-effa-4ebf-8785-234e6896a088)

## Contoh output hasil
Berikut adalah output dari kode Python yang digunakan:

![diawal output](https://github.com/user-attachments/assets/0eaf3a23-4a82-40df-bc62-df90bc33a865)
![ouput akhir](https://github.com/user-attachments/assets/86c95e39-11e0-4847-ba27-ae2bdb399e4e)



