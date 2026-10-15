# 📘 Laporan Praktikum Pertemuan Ke-1 dan 2

🧑‍🎓 **Rizwan Fauziani Ilham - 4524210094**

# 💻 Praktikum Pemrograman Berbasis Web

Project ini merupakan hasil praktikum Pemrograman Berbasis Web (PBW) yang dibuat menggunakan PHP dan HTML. Pada pertemuan ini, terdapat dua program sederhana, yaitu halaman biodata mahasiswa dan kalkulator sederhana.

Melalui project ini, saya mempelajari penggunaan variabel, array, function, percabangan, perulangan, form HTML, serta pemrosesan data menggunakan PHP.

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.2-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white" alt="XAMPP">
</p>

## 📋 Daftar Isi

- [Tentang Praktikum](#-tentang-praktikum)
- [Program yang Dibuat](#-program-yang-dibuat)
- [Fitur Utama](#-fitur-utama)
- [Tech Stack](#-tech-stack)
- [Persyaratan Sistem](#-persyaratan-sistem)
- [Instalasi dan Menjalankan Program](#-instalasi-dan-menjalankan-program)
- [Struktur Project](#-struktur-project)
- [Materi yang Dipelajari](#-materi-yang-dipelajari)
- [Lisensi](#-lisensi)

## 🎯 Tentang Praktikum

Praktikum ini berfokus pada dasar-dasar pemrograman web menggunakan PHP. Program dibuat untuk memahami bagaimana PHP memproses data dan menampilkan hasilnya pada halaman web.

Terdapat dua program yang dibuat, yaitu:

1. **Biodata Mahasiswa** — Menampilkan data mahasiswa dan menentukan predikat berdasarkan nilai IPK.
2. **Kalkulator Sederhana** — Melakukan operasi matematika berdasarkan angka dan operator yang dipilih pengguna.

## ✨ Program yang Dibuat

### 1. 🧑 Biodata Mahasiswa

File: `biodata.php`

Program biodata menampilkan informasi mahasiswa yang disimpan dalam array PHP. Data tersebut kemudian ditampilkan menggunakan perulangan `foreach`.

**Informasi yang ditampilkan:**

- NIM
- Nama mahasiswa
- Program studi
- Semester
- IPK
- Predikat berdasarkan IPK

Program menggunakan function `statusKelulusan()` untuk menentukan predikat berdasarkan nilai IPK.

| Rentang IPK | Predikat |
|---|---|
| IPK ≥ 3,50 | Sangat Memuaskan |
| IPK ≥ 3,00 dan < 3,50 | Memuaskan |
| IPK < 3,00 | Perlu Peningkatan |

### 2. 🧮 Kalkulator Sederhana

File: `kalkulator.php`

Kalkulator sederhana digunakan untuk melakukan perhitungan matematika melalui form HTML. Pengguna dapat memasukkan dua angka dan memilih operator yang tersedia.

**Operasi yang tersedia:**

| Operator | Operasi |
|---|---|
| `+` | Penjumlahan |
| `-` | Pengurangan |
| `*` | Perkalian |
| `/` | Pembagian |

Program memproses input menggunakan metode `POST` dan menentukan perhitungan berdasarkan operator dengan struktur `switch`.

Program juga memiliki validasi sederhana untuk menangani pembagian dengan nol dan operator yang tidak valid.

## 🛠️ Fitur Utama

- ✅ Menampilkan biodata mahasiswa.
- ✅ Menyimpan data biodata menggunakan array PHP.
- ✅ Menggunakan perulangan `foreach` untuk menampilkan data.
- ✅ Menentukan predikat IPK menggunakan function dan percabangan `if`.
- ✅ Melakukan penjumlahan, pengurangan, perkalian, dan pembagian.
- ✅ Mengambil input pengguna melalui form HTML.
- ✅ Memproses data form menggunakan metode `POST`.
- ✅ Menangani pembagian dengan nol.
- ✅ Menampilkan hasil perhitungan pada halaman web.
- ✅ Menggunakan `htmlspecialchars()` untuk membantu mengamankan output yang ditampilkan.

## 💻 Tech Stack

### Backend

- **PHP** — Memproses data, menjalankan logika program, dan menghitung hasil operasi matematika.

### Frontend

- **HTML5** — Membuat struktur halaman, form input, pilihan operator, dan tombol.

### Development Tools

- **XAMPP** — Menyediakan lingkungan server lokal untuk menjalankan PHP.
- **Visual Studio Code** — Editor kode untuk menulis dan mengubah source code.
- **Web Browser** — Menampilkan hasil program yang dijalankan melalui server lokal.

## ⚙️ Persyaratan Sistem

Sebelum menjalankan program, pastikan perangkat sudah memiliki:

- XAMPP dengan Apache.
- Web browser, seperti Google Chrome atau Mozilla Firefox.
- Editor kode, seperti Visual Studio Code.

Program ini tidak memerlukan database karena data biodata disimpan langsung dalam array PHP dan kalkulator hanya melakukan perhitungan berdasarkan input pengguna.

## 🚀 Instalasi dan Menjalankan Program

### 1. Download atau Clone Repository

Clone repository dari GitHub:

```bash
git clone https://github.com/RizwanFI94/4524210094_RIZWANFAUZIANIILHAM_PBW-A_P01-P02.git
```

Masuk ke folder project:

```bash
cd 4524210094_RIZWANFAUZIANIILHAM_PBW-A_P01-P02
```

### 2. Pindahkan Folder ke htdocs

Salin folder project ke direktori `htdocs` pada instalasi XAMPP.

Contoh lokasi:

```text
C:\xampp\htdocs\4524210094_RIZWANFAUZIANIILHAM_PBW-A_P01-P02\
```

Pastikan file PHP berada di dalam folder `Praktikum1`.

### 3. Jalankan Apache

1. Buka XAMPP Control Panel.
2. Klik **Start** pada Apache.
3. Pastikan Apache berjalan tanpa error.

### 4. Jalankan Program Biodata

Buka browser dan akses:

```text
http://localhost/4524210094_RIZWANFAUZIANILHAM_PBW-A_P01-P02/Praktikum1/biodata.php
```

Halaman akan menampilkan biodata mahasiswa beserta predikat IPK.

### 5. Jalankan Program Kalkulator

Buka alamat berikut pada browser:

```text
http://localhost/4524210094_RIZWANFAUZIANILHAM_PBW-A_P01-P02/Praktikum1/kalkulator.php
```

Masukkan dua angka, pilih operator matematika, lalu klik tombol **Hitung** untuk melihat hasilnya.

## 📁 Struktur Project

```text
4524210094_RIZWANFAUZIANILHAM_PBW-A_P01-P02/
├── Praktikum1/
│   ├── biodata.php
│   └── kalkulator.php
└── README.md
```

**Penjelasan file:**

- `biodata.php` — Program untuk menampilkan biodata dan predikat IPK mahasiswa.
- `kalkulator.php` — Program untuk melakukan operasi matematika sederhana.
- `README.md` — Dokumentasi project praktikum.

## 📚 Materi yang Dipelajari

Melalui praktikum ini, beberapa materi dasar PHP yang dipelajari meliputi:

1. **Variabel** — Menyimpan nilai yang digunakan dalam program.
2. **Array** — Menyimpan beberapa data biodata dalam satu variabel.
3. **Function** — Membuat fungsi untuk menentukan predikat IPK.
4. **Percabangan `if-else`** — Menentukan hasil berdasarkan kondisi tertentu.
5. **Perulangan `foreach`** — Menampilkan setiap data yang terdapat dalam array.
6. **Form HTML** — Menerima input dari pengguna.
7. **Metode `POST`** — Mengirim data form ke PHP untuk diproses.
8. **Struktur `switch`** — Menentukan operasi matematika sesuai operator yang dipilih.
9. **Validasi sederhana** — Menangani pembagian dengan nol dan operator tidak valid.
10. **Output PHP dan HTML** — Menampilkan hasil pemrosesan data pada halaman web.

## 📜 Lisensi

Project ini dibuat untuk keperluan pembelajaran dan penyelesaian tugas praktikum Pemrograman Berbasis Web.

---

<p align="center">
  Made with ❤️ by Rizwan Fauziani Ilham
</p>
