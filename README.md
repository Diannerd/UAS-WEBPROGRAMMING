📘 sicad (Sistem Catat Data Informatika)

sicad adalah aplikasi berbasis web untuk Sistem Pengelolaan Nilai Mahasiswa yang memungkinkan dosen mengelola nilai akademik dan mahasiswa melihat hasil studinya secara terstruktur.
Aplikasi ini dibangun sebagai project CRUD Backend & Frontend dengan autentikasi login menggunakan cookies.

🚀 Fitur Utama
🔐 Autentikasi & Autorisasi

Login menggunakan cookies

Role pengguna:

Admin

Dosen

Mahasiswa

📚 Manajemen Akademik (CRUD)

Users (admin, dosen, mahasiswa)

Courses (mata kuliah)

Assignments (tugas, UTS, UAS)

Grades (nilai mahasiswa)

📊 Pengelolaan Nilai

Dosen dapat:

Menginput dan mengedit nilai tugas, UTS, dan UAS

Melihat rekap nilai per mata kuliah

Mahasiswa dapat:

Melihat nilai per mata kuliah

Mengakses kartu hasil studi (KHS)

📁 Export Data

Excel (.xlsx)

Rekap nilai mahasiswa per kelas / mata kuliah

PDF (.pdf)

Kartu Hasil Studi (KHS) mahasiswa

🧩 Struktur Data Utama

Users

id

name

email

password

role (admin / dosen / mahasiswa)

Courses

id

course_name

course_code

lecturer_id

Assignments

id

course_id

title

type (tugas / UTS / UAS)

Grades

id

student_id

assignment_id

score

🛠️ Teknologi yang Digunakan

(Sesuaikan dengan stack yang kamu pakai)

Backend

Node.js / Laravel / Django

REST API

Authentication menggunakan Cookies

Database: MySQL / PostgreSQL

Frontend

React / Vue / Blade / HTML-CSS-JS

Axios / Fetch API

Responsive UI

Export

Excel: xlsx / exceljs

PDF: pdfkit / dompdf

🔄 Alur Sistem

User login → session disimpan di cookies

Sistem mengecek role user

Dosen mengelola nilai mahasiswa

Mahasiswa melihat nilai & KHS

Admin mengelola data master

Data dapat diexport ke Excel & PDF

🎯 Tujuan Project

Project ini dibuat untuk memenuhi Progress UAS dengan ketentuan:

✅ Backend & Frontend

✅ Login Auth menggunakan Cookies

✅ CRUD Data

✅ Export Excel & PDF

✅ Topik Sistem Akademik

📌 Catatan

Project ini bersifat akademik dan dapat dikembangkan lebih lanjut dengan fitur:

Grafik nilai

IPK otomatis

Approval nilai

Notifikasi

👨‍💻 Author

Nama: [Isi Nama Kamu]
Program Studi: Informatika
Universitas: [Isi Nama Kampus]