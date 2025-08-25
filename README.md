Sistem Manajemen Materi Safety
Aplikasi web sederhana untuk mengelola dan menyimpan materi pembelajaran safety secara online. Proyek ini dibangun dengan HTML, CSS, dan JavaScript, menggunakan Supabase sebagai backend database dan penyimpanan file.

Fitur Utama
Menambah, mengedit, dan menghapus materi (dengan judul, deskripsi, dan gambar).

Melihat daftar materi dalam tampilan grid yang rapi.

Tampilan responsif (mobile-friendly).

Penyimpanan data dan gambar yang persisten menggunakan Supabase.

Teknologi yang Digunakan
Frontend: HTML, CSS, JavaScript

Backend: Supabase (Database PostgreSQL & Storage)

Hosting: GitHub Pages

Cara Mengatur Proyek (Deployment)
Kloning Repositori ini:

git clone https://github.com/username-anda/nama-repo.git

Konfigurasi Supabase:

Buat proyek baru di Supabase.

Salin Project URL dan anon public key Anda.

Buka file browser.html dan ganti placeholder dengan kunci Anda.

Buat Tabel & Storage di Supabase:

Buat tabel bernama materi dengan kolom: id, judul, deskripsi, gambar, tanggal.

Buat bucket materi-images di Supabase Storage.

Pastikan Anda mengatur kebijakan (policy) agar tabel dan bucket dapat diakses publik (seperti yang dijelaskan dalam panduan).

Akses Aplikasi:

Setelah file diunggah ke repositori, aktifkan GitHub Pages dari menu Settings.

Akses aplikasi Anda melalui URL yang disediakan oleh GitHub Pages.

Dibuat oleh: [Nama Anda]
