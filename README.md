# Lab8
Tugas Praktikum  Mata Kuliah Program Komputer dan Praktek
==========================================================================================================================

**Deskripsi**
Program ini merupakan aplikasi berbasis teks untuk mengelola data mahasiswa menggunakan pendekatan **Object-Oriented Programming (OOP)**. 

Program ini memiliki kemampuan untuk menambahkan, menampilkan, menghapus, dan mengubah data mahasiswa.

**Fitur Program**

Menambahkan Data Mahasiswa

> Pengguna dapat memasukkan nama dan nilai mahasiswa untuk disimpan.

Menampilkan Data Mahasiswa
    
> Program akan mencetak daftar semua mahasiswa beserta nilainya.

Menghapus Data Mahasiswa

> Pengguna dapat menghapus data mahasiswa berdasarkan nama.

Mengubah Data Mahasiswa

> Pengguna dapat memperbarui nilai mahasiswa berdasarkan nama.

Menu Interaktif

> Program menggunakan menu interaktif untuk memudahkan navigasi pengguna.

**Struktur Kelas**
Class Mahasiswa

Class ini bertanggung jawab untuk mengelola data mahasiswa.

Atribut:

**__data_mahasiswa**: List privat untuk menyimpan data mahasiswa.

Metode:
**tambah(nama, nilai)**: Menambahkan data mahasiswa baru.

**tampilkan()**: Menampilkan semua data mahasiswa.

**hapus(nama)**: Menghapus data mahasiswa berdasarkan nama.

**ubah(nama, nilai_baru)** : Mengubah nilai mahasiswa berdasarkan nama.

__find_by_name(nama): Metode privat untuk mencari data mahasiswa berdasarkan nama.

**Class Menu**

Class ini bertanggung jawab untuk menyediakan antarmuka pengguna.

Atribut:

mahasiswa: Objek dari kelas Mahasiswa.

Metode:

tampilkan_menu(): Menampilkan menu utama dan menangani input pengguna.

__menu_tambah(): Menangani input untuk menambahkan data mahasiswa.

__menu_hapus(): Menangani input untuk menghapus data mahasiswa.

__menu_ubah(): Menangani input untuk mengubah data mahasiswa.

Cara Menjalankan Program

Pastikan Python sudah terinstall pada sistem Anda.

Simpan kode dalam file Python (misalnya main.py).

Jalankan file menggunakan perintah:
Tugas Lab 8.py

Pilih opsi pada menu utama sesuai kebutuhan Anda:

1: Tambah Data

2: Tampilkan Data

3: Hapus Data

4: Ubah Data

5: Keluar

**Diagram Class**
![395343798-b39bd0c5-60c0-48a2-8a15-a622b7e0312b](https://github.com/user-attachments/assets/1ed6eb3d-fde3-4118-a586-ca07d507edc1)

**FlowChart**
![395340670-e9131640-a2e0-4870-bace-478b3bd37aae](https://github.com/user-attachments/assets/b1aec95c-6c5d-40f1-9e06-4753126ade5b)

**Code Program**
![Cuplikan layar 2024-12-13 085053](https://github.com/user-attachments/assets/c03cde52-77e3-4a05-a69c-b0d97a07b95e)
![Cuplikan layar 2024-12-13 085134](https://github.com/user-attachments/assets/2d091505-d048-48b7-a3d8-3de3080c6b3b)
![Cuplikan layar 2024-12-13 085158](https://github.com/user-attachments/assets/caa166c2-810e-426d-a8eb-540ffa77ab35)

**Hasil Program**
![Cuplikan layar 2024-12-13 085218](https://github.com/user-attachments/assets/ff1bc61b-d2ee-4a39-b2e4-716dabcd5d55)
![Cuplikan layar 2024-12-13 085234](https://github.com/user-attachments/assets/c77a5ece-7abe-48d2-bf8c-8f2a55a200d1)

