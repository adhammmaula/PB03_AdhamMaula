# PB03_AdhamMaula

Aplikasi ini dikembangkan untuk memenuhi Tugas Pertemuan 3 pada mata kuliah Pemrograman Bergerak. Tujuan utama dari aplikasi ini adalah untuk merancang dan menampilkan antarmuka statis berupa Profil Mahasiswa / Portofolio Sederhana menggunakan teknologi modern Android, yaitu Jetpack Compose dan Material 3. Proyek ini mendemonstrasikan penerapan komponen tata letak (Row, Column, Box), penggunaan Modifier chain, penerapan tema Material, serta pembuatan custom composable yang dapat digunakan kembali, sepenuhnya tanpa menggunakan layout XML.

Cara Penggunaan (Cara Menjalankan Aplikasi)
1. Lakukan clone repositori ini atau unduh source code dalam bentuk ZIP.
2. Buka proyek ini menggunakan aplikasi Android Studio versi terbaru.
3. Tunggu beberapa saat hingga proses sinkronisasi Gradle selesai sepenuhnya (indikator loading di bawah layar hilang).
4. Untuk melihat kode dan pratinjau desain, buka file app/src/main/java/com/example/tugasweek3/MainActivity.kt dan klik tab Split atau Design di pojok kanan atas untuk melihat @Preview.
5. Untuk menjalankan aplikasi, pilih emulator yang tersedia (misalnya Pixel 7 API 37) atau sambungkan perangkat Android fisik Anda, lalu tekan tombol Run

Struktur Composable Utama
1. ProfileScreen
Merupakan composable utama pembungkus layar. Menggunakan tata letak Column untuk menyusun seluruh bagian profil dari atas ke bawah secara terpusat dengan jarak antar elemen yang konsisten menggunakan Arrangement.spacedBy.
2. ProfileHeader
Bagian atas profil yang menampilkan foto, nama lengkap mahasiswa, dan teks deskripsi status akademik menggunakan gaya MaterialTheme.typography.
3. ProfileInfoCard
Bagian tengah aplikasi yang dibungkus dengan komponen Card. Bagian ini berfungsi untuk menampung sekumpulan informasi akademik.
4. InfoRow
Sebuah custom composable yang bersifat reusable. Terdiri dari sebuah Row dengan pengaturan Arrangement.SpaceBetween untuk menampilkan label di sisi kiri (misal: "NIM") dan nilainya di sisi kanan (misal: "0102524001") secara sejajar.
5. ActionFooter
Bagian paling bawah dari layar yang berisi sebuah komponen Button lebar penuh lengkap dengan ikon surat (email) yang berfungsi sebagai area aksi (Call to Action) "Hubungi Saya".

<img width="1915" height="1005" alt="Screenshot 2026-10-15 110617" src="https://github.com/user-attachments/assets/8d69619d-34ca-45bb-a04b-7bafb5b964b9" />

