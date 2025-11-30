# praktikum6
# 👨‍🎓 Program Manajemen Nilai Mahasiswa Sederhana (CRUD)

Program ini dibuat untuk memenuhi Tugas Praktikum mata kuliah [Isi Nama Mata Kuliah Anda] yang mengaplikasikan penggunaan fungsi dasar dalam bahasa pemrograman Python untuk mengelola data mahasiswa.

Program ini berfungsi sebagai sistem manajemen data sederhana (CRUD: Create, Read, Update, Delete) untuk daftar nilai mahasiswa.

---

## 1. Flowchart Program

Berikut adalah diagram alir (*flowchart*) yang menjelaskan alur kerja utama program, dimulai dari menu utama hingga pemanggilan fungsi-fungsi pengelolaan data.



*(Catatan: Sisipkan gambar flowchart yang telah Anda buat di sini.)*

---

## 2. Penjelasan Program

### A. Struktur Data

Data mahasiswa disimpan dalam sebuah **list** bernama `data_mahasiswa`. Setiap data mahasiswa diwakili oleh sebuah **dictionary** yang memiliki dua *key* utama:
* `"nama"`: Menyimpan nama mahasiswa (string).
* `"nilai"`: Menyimpan nilai mahasiswa (string/integer).

### B. Fungsi-Fungsi Utama

Program ini diorganisir menggunakan empat fungsi utama yang beroperasi langsung pada `data_mahasiswa`:

| Fungsi | Deskripsi | Operasi CRUD |
| :--- | :--- | :--- |
| `tambah()` | Meminta input **Nama** dan **Nilai**, kemudian membuat *dictionary* baru dan menambahkannya ke dalam list `data_mahasiswa`. | **Create** |
| `tampilkan()` | Menampilkan seluruh isi list `data_mahasiswa` secara terstruktur dalam format daftar bernomor. | **Read** |
| `hapus(nama)` | Mencari data mahasiswa berdasarkan **nama**. Jika nama ditemukan, data tersebut akan dihapus dari list. | **Delete** |
| `ubah(nama)` | Mencari data mahasiswa berdasarkan **nama**. Jika ditemukan, pengguna akan diminta memasukkan **Nilai Baru** untuk memperbarui data tersebut. | **Update** |

### C. Alur Program

1.  Program dimulai dengan menampilkan **Menu Utama** yang berisi 5 opsi (Tambah, Tampilkan, Hapus, Ubah, Keluar).
2.  Pengguna diminta memasukkan nomor pilihan (1-5).
3.  Berdasarkan pilihan, program akan memanggil fungsi yang relevan (`tambah`, `tampilkan`, `hapus`, atau `ubah`).
4.  Jika pilihan adalah `3` atau `4`, program akan meminta input **nama** sebagai argumen fungsi untuk menentukan data mana yang akan dimodifikasi atau dihapus.
5.  Setelah fungsi selesai dijalankan, program akan kembali menampilkan **Menu Utama** hingga pengguna memilih opsi `5` (**Keluar**).

---

## 🚀 Cara Menjalankan Program

1.  Pastikan Anda memiliki Python terinstal di sistem Anda.
2.  Simpan kode program ke dalam sebuah file, misalnya `manajemen_nilai.py`.
3.  Buka terminal/Command Prompt dan jalankan perintah:
    ```bash
    python manajemen_nilai.py
    ```
