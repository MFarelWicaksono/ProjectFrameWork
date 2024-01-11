<a name="br1"></a> 



<a name="br2"></a> 

**Bab I Pendahuluan**

**1.1 Tujuan**

Pusat informasi dan konseling Konsultasi (PIK K) adalah wadah kegiatan program untuk

siswa bisa berkonsultasi dengan Guru BK di SMA IT Al - Ittihad. Tujuan dari program ini

dibangun adalah untuk memudahkan penentuan waktu dan lokasi sehingga memudahkan

bagi para guru siswa dalam mengatur penjadwalan konsultasi. Sehingga ini bisa menjadi

acuan untuk membangun perangkat lunak “PUSAT INFORMASI DAN KONSELING

KONSULTASI”.

**1.2 Lingkup**

Pusat Informasi dan Konseling Konsultasi (PIK K) merupakan web yang kami bangun di

SMA IT Al - Ittihad untuk mempermudah penentuan waktu dan lokasi sehingga

memudahkan bagi para guru siswa dalam mengatur penjadwalan konsultasi.

**1.3 Akronim, singkatan, definisi**

**Istilah**

SRS

**Definisi**

Software Requirement Specification

Digunakan untuk mengakses aplikasi

Login

Software Requirement Perangkat lunak yang akan dibuat dan sebagai menjembatani

Specification

komunikasi pembuat dengan pengguna

Use Case

Situasi dimana sistem anda digunakan untuk memenuhi satu

atau lebih kebutuhan pemakaian anda

**1.4 Referensi**

Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :

**1.5 Overview**

Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada aplikasi. Menjelaskan

gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir

menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3

merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.



<a name="br3"></a> 

**BAB II Gambaran Umum**

Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya

ialah perkembangan teknologi di bidang software engineering dimana software engineering

dapat digunakan dalam kehidupan sehari - hari .dalam studi kasus Proyek kali ini kami

mewawancarai salah satu sekolah yang ada di pekanbaru yaitu SMA IT Al - Ittihad. Kasus

yang kami peroleh bernama Pusat Informasi dan Konseling Konsultasi. Maka dari itu kami

sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan SMA IT

Al - Ittihad, software yang kami buat ini berbasis website, pada sistem ini para siswa dapat

menentukan siapa yang akan menjadi konselor mereka dan dapat menentukan waktu dan

lokasi yang diinginkan.

**2.1 Perspektif Produk**

Pusat informasi dan konseling Konsultasi SMA Al - Ittihad adalah sebuah sistem

penjadwalan konseling yang diaplikasikan pada website. Terdapat 2 jenis yaitu admin dan

konseli. Pengolahan data di kelola oleh admin pada website dan konseli melihat

ketersediaan konselor, lokasi, jadwal dan dapat mendaftar sebagai konseli.



<a name="br4"></a> 

**2.1.1 Antarmuka Sistem**



<a name="br5"></a> 

**2.1.2 Antarmuka Pengguna**

● Mockup Admin ( Website )

Pada halaman login diminta untuk mengisi

username dan password.

Pada halaman home user akan langsung

melihat artikel-artikel yang ada di halaman

home dan dapat melihat berbagai menu di

sebelah kiri

Pada halaman Konselor user bisa melihat

profil-profil, bidang dan ketersediaan dari

konselor-konselor yang ada.

Pada halaman Form Konsul user nanti nya

akan mengisi form yang tersedia untuk

mengajukan konsultasi.

Pada halaman Rekap Data Pengajuan ini

User dapat melihat riwayat pengajuan

Pada halaman Home Admin, Admin bisa

menambah dan menghapus artikel.



<a name="br6"></a> 

Pada halaman Konselor di Admin, Admin

dapat menambah dan mengedit data-data

dari konselor.

Pada halaman tambah data konselor ini

admin bisa menambahkan data untuk

konselor dengan memasukan foto, nama,

motto, dan bidang

Pada halaman Konseli Admin dapat melihat Pada halaman Rekap konseling ini Admin

data konseli yang mengajukan konseling. dapat menghapus data rekapan.



<a name="br7"></a> 

**2.1.3 Antarmuka Perangkat Keras**

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Pusat

Informasi dan Konseling Konsultasi antara lain :

1\. PC / Laptop untuk menjalankan web ini admin membutuhkan sebuah PC yang

menggunakan OS WIndows, Linux, atau MAC dan sudah terinstall browser.

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Pusat

Informasi dan Konseling Konsultasi antara lain :

1\. Kabel Lan UTP RJ45

2\. Modem

3\. Wifi

**2.1.6 Batasan Memori**

Tidak ada

**2.1.7 Operasi - Operasi**

Operasi

Fungsi

Digunakan untuk mengakses aplikasi

Digunakan untuk memasukkan data-data

Login

Input Data



<a name="br8"></a> 

Kembali

Hapus

Edit

Digunakan untuk kembali ke halaman sebelumnya

Digunakan untuk menghapus data

Digunakan untuk mengubah data

View

Digunakan untuk menampilkan data

Digunakan untuk menyimpan data

Digunakan untuk mencetak laporan

Simpan

Cetak

**2.1.8 Kebutuhan Adaptasi**

Tidak ada

**2.2 Spesifikasi Kebutuhan Fungsional**



<a name="br9"></a> 

**2.2.1 Konseli Login**

Use Case : Login

Diagram :

Deskripsi Singkat Konseli melakukan login terlebih dahulu sebelum masuk ke tampilan

home, apabila tidak dapat mengakses atau gagal konseli dapat meminta kepada admin

dibuatkan akunnya. Deskripsi langkah - langkah :

1\. Konseli melakukan login dengan memasukkan username dan password

2\. Sistem melakukan validasi login

3\. Bila sukses sistem akan mengarahkan ke halaman utama

4\. Bila gagal sistem akan menampilkan pesan kesalahan dan menampilkan halaman

login kembali

Xref : Bagian 3.2.1, Konseli Login

**2.2.2 Konseli Melihat Ketersediaan Konselor**

Use Case : Melihat Ketersediaan Konselor

Diagram :

Deskripsi Singkat Konseli dapat melihat ketersediaan konselor pada menu konselor.

Deskripsi langkah - langkah :

1\. Konseli mengklik menu konselor

2\. Sistem akan menampilkan daftar konselor, nama, bidang beserta jadwal konselor

Xref : Bagian 3.2.2, Konseli Melihat Ketersedian Konselor



<a name="br10"></a> 

**2.2.3 Konseli Mengisi Formulir Konseling**

Use Case : Mengisi Formulir Konseling

Diagram :

Deskripsi Singkat Konseli dapat mengisi formulir konseling.

Deskripsi langkah - langkah :

1\. Konseli mengklik menu form pengajuan

2\. Sistem akan menampilkan halaman form pengajuan

3\. Konseli mengisi form pengajuan

4\. Konseli akan dihubungi oleh admin jika pengajuan konsultasi diterima

Xref : Bagian 3.2.3, Konseli Mengisi Formulir Konseling

**2.2.4 Admin Login**

Use Case : Login

Diagram :

Deskripsi Singkat Admin melakukan login terlebih dahulu sebelum masuk ke tampilan home

dengan memasukkan username dan password, apabila login gagal maka sistem akan

menampilkan pesan kesalahan / error.

Deskripsi langkah - langkah :

1\. Admin melakukan login dengan memasukkan username dan password

2\. Sistem melakukan validasi login

3\. Bila sukses sistem akan mengarahkan ke halaman utama

4\. Bila gagal sistem akan menampilkan pesan kesalahan dan menampilkan halaman

login kembali

Xref : Bagian 3.2.4, Admin Login



<a name="br11"></a> 

**2.2.5 Admin Mengelola Rekap Konsultasi**

Use case : Mengelola Rekap Konsultasi

Diagram :

Deskripsi Singkat Admin mengelola rekap konsultasi di dalam nya admin dapat menghapus

rekap konsultasi.

Deskripsi langkah - langkah :

1\. Admin mengklik menu rekap konsultasi

2\. Sistem akan menampilkan halaman menu rekap konsultasi

Xref : Bagian 3.2.5, Admin Mengelola Data Konseli

**2.2.6 Admin Mengelola Data Konseli**

Use Case : Mengelola Data Konseli

Diagram :

Deskripsi Singkat Admin mengelola data konseli didalam nya admin dapat menghapus,

mengedit data konseli

Deskripsi langkah-langkah:

1\. Admin mengklik menu konseli

2\. Sistem akan menampilkan halaman menu konseli

Xref : Bagian 3.2.6, Admin Mengelola Data Konseli



<a name="br12"></a> 

**2.2.7 Admin Mengelola Data Konselor**

Use Case : Mengelola Data Konselor

Diagram :

Deskripsi Singkat Admin mengelola data konselor, admin dapat menambahkan,

menghapus, mengedit data konselor

Deskripsi langkah-langkah:

1\. Admin mengklik menu konselor

2\. Sistem akan menampilkan halaman menu konselor

Xref : Bagian 3.2.7, Admin Mengelola Data Konselor

**2.2.8 Admin Menerima Pengajuan Konseling**

Use Case : Mengkonfirmasi Pemakaian Konseling

Diagram :

Deskripsi Singkat Admin mengelola data pengajuan, admin dapat menambahkan,

menghapus, mengedit data pengajuan

Deskripsi langkah-langkah:

1\. Admin mengklik menu konsultasi

2\. Sistem akan menampilkan halaman menu konsultasi

Xref : Bagian 3.2.8, Admin Menerima Pengajuan Konseling



<a name="br13"></a> 

**2.3 Spesifikasi Kebutuhan Non-Fungsional**

● Tabel Kebutuhan Non-Fungsional

No

1

Deskripsi

Semua interface dan fungsi menggunakan Bahasa Indonesia

Perangkat Lunak dapat dipakai di semua platform OS ( Admin dan Konseli )

2

**2.4 Karakteristik Pengguna**

Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi

dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

**2.5 Batasan - Batasan**

● Perangkat lunak web hanta dijalalnkan di windows (7,8,10).

● Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan

tidak semua fungsi yang ada dapat dilaksanakan.

**2.6 Asumsi - Asumsi**

Tidak ada

**2.7 Kebutuhan Penyeimbang**

Tidak ada

**BAB III Requirement Specification**

**3.1 Persyaratan Antarmuka Eksternal**

Salah satu cara mengakses aplikasi ini yaitu dengan membuat akun terlebih dahulu untuk

yang belum mempunyai akun, login melalui aplikasi ini dengan mencantumkan username

dan password kemudian sistem akan memvalidasi login. Setelah login berhasil sistem akan

menampilkan halaman utama.



<a name="br14"></a> 

**3.2 Functional Requirement**

Logika Struktur terdapat pada bagian 3.3.1

**3.2.1 Konseli Login**

Nama Fungsi

Xref

Login

Bagian 2.2.1 Konseli Login

Trigger

Membuka web Pusat Informasi Konseling dan Konsultasi

Halaman login

Precondition

Basic Path

1\. Konseli melakukan login dengan memasukkan

username dan password

2\. Sistem melakukan validasi login

3\. Bila sukses sistem akan mengarahkan ke halaman

utama

4\. Bila gagal sistem akan menampilkan pesan

kesalahan dan menampilkan halaman login

kembali

Alternatif

Tidak ada

Post Condition

Konseli dapat login dan mengakses website Pusat

Informasi Konseling dan Konsultasi

Exception Push

Username dan password salah

**3.2.2 Konseli Melihat Ketersediaan Konselor**

Nama Fungsi

Xref

Melihat ketersediaan konselor

Bagian 2.2.2 Konseli Melihat Ketersediaan Konselor

Konseli menekan menu konselor

Trigger

Precondition

Basic Path

Halaman Utama Konseli

1\. Konseli mengklik menu konselor

2\. Sistem akan menampilkan daftar konselor, nama,

bidang beserta jadwal konselor

Alternatif

Tidak ada

Post Condition

Halaman menu konselor



<a name="br15"></a> 

Exception Push

Tidak ada

**3.2.3 Konseli Mengisi Formulir Konseling**

Nama Fungsi

Xref

Mengisi formulir Konseling

Bagian 2.2.3 Konseli Mengisi Formulir Konseling

Konseli menekan menu Form Konseling

Halaman Utama Konseli

Trigger

Precondition

Basic Path

1\. Konseli mengklik menu form pengajuan

2\. Sistem akan menampilkan halaman form

pengajuan

3\. Konseli mengisi form pengajuan

Alternatif

Tidak ada

Post Condition

Konseli dapat melakukan konseling sesuai jadwal dan

lokasi yang sudah disepakati

Exception Push

Tidak ada

**3.2.4 Admin Login**

Nama Fungsi

Xref

Login

Bagian 2.2.4 Admin Login

Trigger

Membuka web Pusat Informasi Konseling dan Konsultasi

Halaman login

Precondition

Basic Path

1\. Admin melakukan login dengan memasukkan

username dan password

2\. Sistem melakukan validasi login

3\. Bila sukses sistem akan mengarahkan ke halaman

utama

4\. Bila gagal sistem akan menampilkan pesan

kesalahan dan menampilkan halaman login

kembali

Alternatif

Tidak ada

Post Condition

Admin dapat login dan mengakses website Pusat

Informasi Konseling dan Konsultasi



<a name="br16"></a> 

Exception Push

Username dan password salah

**3.2.5 Admin Mengelola Rekap Konsultasi**

Nama Fungsi

Xref

Mengelola rekap konsultasi

Bagian 2.2.5 Admin Mengelola Rekap Konsultasi

Admin menekan menu Rekap Konsultasi

Halaman Utama Admin

Trigger

Precondition

Basic Path

1\. Admin mengklik menu rekap konsultasi

2\. Sistem akan menampilkan halaman menu rekap

konsultasi

Alternatif

Tidak ada

Post Condition

Exception Push

Halaman Rekap Konsultasi

Tidak ada

**3.2.6 Admin Mengelola Data Konseli**

Nama Fungsi

Xref

Mengelola Data Konseli

Bagian 2.2.6 Admin Mengelola Data Konseli

Admin menekan menu Konseli

Halaman Utama Admin

Trigger

Precondition

Basic Path

1\. Admin mengklik menu konseli

2\. Sistem akan menampilkan halaman menu konseli

Alternatif

Tidak ada

Post Condition

Exception Push

Halaman Konseli

Tidak ada

**3.2.7 Admin Mengelola Data Konselor**



<a name="br17"></a> 

Nama Fungsi

Xref

Mengelola data konselor

Bagian 2.2.7 Admin Mengelola Data Konselor

Admin menekan menu Konselor

Halaman Utama Admin

Trigger

Precondition

Basic Path

1\. Admin mengklik menu konselor

2\. Sistem akan menampilkan halaman menu konselor

Alternatif

Tidak ada

Post Condition

Exception Push

Halaman Konselor

Tidak ada

**3.2.8 Admin Menerima Pengajuan Konseling**

Nama Fungsi

Xref

Mengkonfirmasi pemakaian konseling

Bagian 2.2.8 Admin Mengkonfirmasi Pemakai Konseling

Admin menekan menu Pengajuan Konseling

Halaman Utama Admin

Trigger

Precondition

Basic Path

1\. Admin mengklik menu konsultasi

2\. Sistem akan menampilkan halaman menu

konsultasi

Alternatif

Tidak ada

Post Condition

Exception Push

Halaman Pengajuan Konseling

Tidak ada



<a name="br18"></a> 

**3.3 Struktur Detail Kebutuhan Non-Fungsional**

**3.3.1 Logika Struktur Data**

**Tabel User**

Data Item

id

Type

Deskripsi

varchar

varchar

varchar

varchar

varchar

varchar

Nomor auto increment id

Berisikan nama dari user

Berisikan password user untuk login

nama

password

role

email

Berisikan email user untuk login

Berisikan nomor hp user

no\_hp

**Tabel Konselor**

Data Item

Type

Deskripsi

nama\_konselor varchar

id\_konselor varchar

status\_konselor varchar

bidang varchar

Berisikan nama dari konselor

Nomor auto increment id\_konselor

Berisikan status konselor

Berisikan bidang untuk konsultasi yang ingin lebih

berfokus pada suatu bidang



<a name="br19"></a> 

motto

varchar

Nomor auto increment id

**Tabel Ajukan**

Data Item

id\_konselor

id\_konseling

id\_lokasi

Type

Deskripsi

varchar

varchar

varchar

varchar

enum

Nomor auto increment id\_konselor

Nomor auto increment id\_konseling

Nomor auto increment id\_lokasi

Nomor auto increment id\_konseli

Berisikan waktu pemakaian konsultasi

Berisikan tanggal pemakaian konsultasi

id\_konseli

waktu

lokasi

enum

**Pembagian Tugas Kelompok**

Abdul Habib Risyik : Use Case dan ERD, Coding Web

Muhammad Amien Rais : Figma dan SRS, PPT dan SRS Akhir

Muhammad Farel Wicaksono : Figma dan SRS, Coding Web

Muhammad Rizki : Figma dan SRS, PPT dan SRS Akhir

