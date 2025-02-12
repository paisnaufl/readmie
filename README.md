FAIZ NAUFAL AKBAR
XII PPLG 2
SMK Negeri 2 Pekanbaru
Rabu, 12 Februari 2025

==================================

# LSP Kasir - Faiz Naufal Akbar (XII PPLG 2)

## Deskripsi
Repositori ini berisi dua sistem **Kasir (Cash Register)** yang berbeda:
1. **Kasir Berbasis Web**: Sistem yang dibangun menggunakan PHP dan MySQL untuk melakukan operasi CRUD.
2. **Kasir Desktop Java**: Aplikasi desktop berbasis Java untuk sistem kasir.

---

## Kasir Berbasis Web (CRUD Operations)

### Role & Kredensial Login

#### 🔹 Administrator
- **Username**: `fL`
- **Password**: `123`
- **Hak Akses**: Dapat mengubah semua data, termasuk data pengguna petugas.

#### 🔹 Petugas
- **Username**: `ji`
- **Password**: `123`
- **Hak Akses**: Tidak dapat mengubah data pengguna petugas, hanya dapat mengelola data lainnya.

---

## Cara Mengimpor Database ke phpMyAdmin

1. **Buat Database Baru**  
   Buat database baru dengan nama **`kasir2`** (database ini digunakan untuk website kasir).

2. **Impor Database**  
   Impor file database yang ada di folder saat ini (`./kasir2.sql`) ke dalam phpMyAdmin.

3. **Akses Website**  
   Masukkan link berikut untuk mengakses website:  
   [http://localhost/kasir/web/login.php](http://localhost/kasir/web/login.php)

4. **Login**  
   Gunakan username dan password yang telah disediakan di atas untuk login ke website kasir.

---

## Kasir Desktop Java

### Kredensial Login
- **Username**: `fL`
- **Password**: `123`

---

## Cara Mengimpor Database ke phpMyAdmin

1. **Buat Database Baru**  
   Buat database baru dengan nama **`penjualanbarang`** (database ini digunakan untuk aplikasi desktop kasir Java).

2. **Impor Database**  
   Impor file database yang ada di folder saat ini (`./penjualanbarang.sql`) ke dalam phpMyAdmin.

3. **Jalankan Aplikasi Desktop**  
   Buka NetBeans (atau compiler Java lainnya) dan buka project kasir di folder:  
   `.\LSP_FAIZ_NAUFAL_AKBAR_XII PPLG 2\PBO_KASIR_JAVA\kasir_desktop\src\penjualan_java`

4. **Login**  
   Gunakan username dan password yang telah disediakan di atas untuk login ke aplikasi desktop kasir.

---

**Aplikasi kasir dapat diakses setelah langkah-langkah di atas selesai.**

