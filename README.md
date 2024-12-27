# Deskripsi Program Validasi Input Pendaftaran Online

Program ini bertujuan untuk memvalidasi data yang diperlukan dalam pendaftaran online. Tiga jenis data yang divalidasi adalah:

## 1. Nama Lengkap
- **Kriteria**: Harus terdiri hanya dari huruf.
- **Metode**: Menggunakan `isalpha()` untuk memeriksa karakter.

## 2. Nomor Telepon
- **Kriteria**: Harus hanya berisi angka.
- **Metode**: Menggunakan `isdigit()` untuk memastikan semua karakter adalah digit.

## 3. Email
- **Kriteria**: Harus mengandung karakter `@` dan `.` setelahnya.
- **Metode**: Memeriksa keberadaan `@` dan `.` di domain.

## Hasil Validasi
- Jika semua input valid, program menampilkan:
  *pendaftaran valid*
- Jika ada kesalahan, program memberikan pesan error yang sesuai.

## Contoh Penggunaan
Pengguna akan diminta untuk memasukkan: Nama lengkap, Nomor telepon, Email. Program kemudian melakukan validasi dan memberikan umpan balik.

## kode perintah 
Berikut adalah contoh kode Python untuk validasi:

![perintah 1](https://github.com/user-attachments/assets/36fddf65-c0ba-4432-9caf-75b596fa2a61)
![perintah 2](https://github.com/user-attachments/assets/6937c6b8-3d4b-4795-90a4-7988d3ba9920)

## hasil screenshout gambar :

![ouput susanti valid](https://github.com/user-attachments/assets/31bbdba1-4374-4da8-b4fd-b691aaa33984)
