<p align="center"><img src="https://imgur.com/cXtB87y.png" width="500"></p>

# 🩺 Sipograf - Sistem Informasi Posyandu dengan KMS

> Sipograf adalah aplikasi yang digunakan untuk pencatatan data balita dan visualisasi KMS (Kartu Menuju Sehat) dalam bentuk grafik pertumbuhan, guna mendukung pemantauan gizi secara efisien dan akurat di Posyandu.


## 🛠 Teknologi yang Digunakan

- **Python** untuk antarmuka pengguna
- **MySQL** sebagai basis data


## 📌 Cara Menggunakan Aplikasi

1. Clone repositori ini ke komputer kamu.

2. Install XAMPP atau software MySQL Server lainnya.

3. Buat database MySQL baru dengan nama `dbsipograf`.

4. Import file `dbsipograf.sql` yang tersedia tersebut melalui phpMyAdmin.

5. Edit konfigurasi koneksi database di file config.py sesuai dengan pengaturan MySQL kamu (host, user, password, dan nama database).

6. Install semua dependensi Python menggunakan perintah pip install -r requirements.txt.

7. Jalankan aplikasi dengan menjalankan file main.py.

8. Setelah aplikasi terbuka, login sebagai petugas dan mulai mengelola data balita, memasukkan data pengukuran, serta melihat grafik pertumbuhan KMS.
   

## 💻 Contoh Tampilan Antarmuka

<p align="center"><img src="https://imgur.com/HTnIUB4.png" width="500"></p>


## 📂 Struktur Proyek 

- **`index.html`** – File utama untuk menjalankan aplikasi

- **`connection.php`** – Pengaturan koneksi database

- **`dbsipograf.sql`** – File SQL untuk membuat database dan tabel

- **`img/`** – Folder untuk gambar/icon

- **`css`** – Berisi file stylesheet untuk mengatur tampilan antarmuka aplikasi
  
-**`penimbangan`** – Berisi data atau logika aplikasi terkait proses penimbangan balita

## ⚙️ Fitur Utama
- Login petugas Posyandu

- Input, edit, dan hapus data balita

- Pencatatan data pengukuran balita (tinggi dan berat badan)

- Visualisasi grafik pertumbuhan berdasarkan KMS

- Cetak grafik atau laporan jika diperlukan


## 📃 Lisensi

Proyek ini dirilis di bawah [MIT License](https://opensource.org/licenses/MIT).  
Bebas digunakan untuk keperluan pribadi maupun komersial dengan atribusi yang sesuai.
