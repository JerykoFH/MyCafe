# MyCafe - Aplikasi Manajemen Kafe (Tugas Besar Dasar Pemrograman)

MyCafe adalah aplikasi Command Line Interface (CLI) berbasis Python yang dirancang untuk membantu pengelolaan operasional kafe. Aplikasi ini dibuat sebagai Tugas Besar (Tubes) untuk mata kuliah Dasar Pemrograman. Aplikasi ini menggunakan file CSV (Comma Separated Values) sebagai basis data penyimpanan lokal.

## Fitur Utama

- **Sistem Autentikasi Admin**
  - Pembuatan akun admin baru (Signup)
  - Login untuk admin
- **Manajemen Menu**
  - Menambahkan menu baru
  - Mengedit informasi menu (nama, harga)
  - Mencari menu
  - Menambah atau update stok menu
- **Manajemen Transaksi**
  - Mencatat transaksi pelanggan (kasir)
  - Melihat riwayat transaksi hari ini atau di hari-hari sebelumnya
  - Fitur "Akhiri Hari" untuk menyimpan rekapitulasi harian
- **Laporan Pendapatan**
  - Menampilkan pendapatan pada hari ini
  - Menampilkan laporan pendapatan berdasarkan riwayat hari yang telah berlalu
- **Manajemen Member**
  - Melihat data pelanggan yang terdaftar sebagai member
- **Database Berbasis CSV**
  - Seluruh data tersimpan secara terstruktur dalam format CSV (`account.csv`, `member.csv`, `menu.csv`, `rating.csv`, `transaksi.csv`).
  - Transaksi harian akan secara otomatis disimpan log-nya dalam file CSV berformat tanggal (opsional).

## Struktur File

- `mainmenu.py` : Berisi program utama aplikasi termasuk logika bisnis dan tampilan antar muka konsol (CLI).
- `logo.py` : Tampilan logo ASCII untuk antarmuka pada saat program dijalankan.
- `lload.py` : Skrip tambahan untuk menampilkan simulasi animasi *loading bar*.
- `test.py` : File testing (uji coba) baris per baris kode.
- `*.csv` : Kumpulan basis data aplikasi (akun, menu, transaksi, dll).

## Cara Menjalankan Program

1. **Prasyarat**
   - Pastikan Python (versi 3.x) telah terinstall pada sistem operasi Anda.
2. **Buka Terminal / Command Prompt**
   - Arahkan ke direktori penyimpanan project ini (misalnya `cd Tubes-Daspro`).
3. **Mulai Aplikasi**
   - Jalankan instruksi berikut:
     ```bash
     python mainmenu.py
     ```
4. **Navigasi Aplikasi**
   - Ikuti opsi menu yang muncul pada layar dengan membalas ketikan nomor yang bersesuaian dengan aksi yang ingin dilakukan.
   - Menu utama menyediakan akses admin untuk melakukan kustomisasi menu makanan & minuman serta pencatatan penjualan dan laporan.

## Kontributor

Dibuat secara kolaboratif oleh tim mahasiswa untuk mata kuliah ProDas:
- **Febrian** (Fokus Modul: Transaksi, Pendapatan, Campur Algoritma)
- **Yosua** (Fokus Modul: Autentikasi / Login / Sign-up, Modul Admin)
- **Jeryko** (Fokus Modul: Manajemen Menu, Animasi, Laporan)
