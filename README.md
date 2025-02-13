# Aplikasi-Perpustakaan-digital-SMK-Muhammadiyah-Kota-Cirebon


## Sistem Informasi Perpustakaan

Proyek ini merupakan aplikasi berbasis web yang dibangun menggunakan PHP untuk mengelola sistem informasi perpustakaan. Aplikasi ini mencakup fitur login, registrasi, dan pengelolaan data perpustakaan.

### Fitur Utama:
- **Manajemen Buku**: Tambah, edit, dan hapus data buku.
- **Manajemen Anggota**: Kelola data anggota perpustakaan.
- **Transaksi Peminjaman**: Catat peminjaman dan pengembalian buku.
- **Autentikasi Pengguna**: Sistem login dan registrasi untuk pengguna.

### Struktur Direktori:
- `app/` : Direktori berisi logika inti aplikasi.
- `assets/` : Berisi file statis seperti CSS, JavaScript, dan gambar.
- `config/` : Konfigurasi database dan pengaturan aplikasi.
- `database/` : Skrip SQL untuk pembuatan tabel dan data awal.
- `function/` : Fungsi PHP pendukung.
- `index.php` : Halaman awal aplikasi.
- `login.php` : Halaman login pengguna.
- `register.php` : Halaman registrasi pengguna.
- `.htaccess` : Konfigurasi untuk mengatur akses direktori.
- `LICENSE` : Lisensi proyek.
- `README.md` : Panduan dan dokumentasi proyek.

### Instalasi:
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/nama-repo.git
   ```
2. Konfigurasi database di `config/`.
3. Jalankan server lokal (XAMPP/Laragon):
   ```bash
   php -S localhost:8000
   ```
4. Akses aplikasi melalui `http://localhost:8000`.
