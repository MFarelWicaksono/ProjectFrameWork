
![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.001.png)
# **Bab I Pendahuluan**
## <a name="_dlxdgssm4st3"></a>**1.1 Tujuan**
Pusat informasi dan konseling Konsultasi (PIK K) adalah wadah kegiatan program untuk siswa bisa berkonsultasi dengan Guru BK di SMA IT Al - Ittihad. Tujuan dari program ini dibangun adalah untuk memudahkan penentuan waktu dan lokasi sehingga memudahkan bagi para guru siswa dalam mengatur penjadwalan konsultasi. Sehingga ini bisa menjadi acuan untuk membangun perangkat lunak “PUSAT INFORMASI DAN KONSELING KONSULTASI”.
## <a name="_h27k7i2131gz"></a>**1.2 Lingkup**
Pusat Informasi dan Konseling Konsultasi (PIK K) merupakan web yang kami bangun di SMA IT Al - Ittihad untuk mempermudah penentuan waktu dan lokasi sehingga memudahkan bagi para guru siswa dalam mengatur penjadwalan konsultasi.
## <a name="_6pe3bsvrd30n"></a>**1.3 Akronim, singkatan, definisi**


|**Istilah**|**Definisi**|
| :- | :- |
|SRS|Software Requirement Specification|
|Login|Digunakan untuk mengakses aplikasi|
|Software Requirement Specification|Perangkat lunak yang akan dibuat dan sebagai menjembatani komunikasi pembuat dengan pengguna|
|Use Case|Situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda|

## <a name="_r5f9m4i6v0il"></a>**1.4 Referensi**
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah : 
## <a name="_c395ppt0z2aq"></a>**1.5 Overview**
Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.
# <a name="_p708b8co7rl1"></a>**BAB II Gambaran Umum**
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari .dalam studi kasus Proyek kali ini kami mewawancarai salah satu sekolah yang ada di pekanbaru yaitu SMA IT Al - Ittihad. Kasus yang kami peroleh bernama Pusat Informasi dan Konseling Konsultasi. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan SMA IT Al - Ittihad, software yang kami buat ini berbasis website, pada sistem ini para siswa dapat menentukan siapa yang akan menjadi konselor mereka dan dapat menentukan waktu dan lokasi yang diinginkan.
## <a name="_frvy97l7db5u"></a>**2.1 Perspektif Produk**
Pusat informasi dan konseling Konsultasi SMA Al - Ittihad adalah sebuah sistem penjadwalan konseling yang diaplikasikan pada website. Terdapat 2 jenis yaitu admin dan konseli. Pengolahan data di kelola oleh admin pada website dan konseli melihat ketersediaan konselor, lokasi, jadwal dan dapat mendaftar sebagai konseli.
### <a name="_anfjpx94rym0"></a>**2.1.1 Antarmuka Sistem**
![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.002.png)
####
####











### <a name="_z5tspbg20q8a"></a><a name="_2w6q3eni5gaw"></a><a name="_s01r45rwy92m"></a>**2.1.2 Antarmuka Pengguna**
- Mockup Admin ( Website )


|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.003.png)|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.004.png)|
| :- | :- |
|Pada halaman login diminta untuk mengisi username dan password.|Pada halaman daftar ini user akan membuat akun dengan inputkan nama, kelas, email dan password.|
|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.005.png)|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.006.png)|
|Pada halaman home user akan langsung melihat artikel-artikel yang ada di halaman home dan dapat melihat berbagai menu di sebelah kiri.|Pada halaman Konselor user bisa melihat profil-profil, bidang dan ketersediaan dari konselor-konselor yang ada.|
|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.007.png)|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.008.png)|
|Pada halaman Form Konsul user nanti nya akan mengisi form yang tersedia  untuk mengajukan konsultasi.|Pada halaman Home Admin, Admin bisa menambah dan menghapus artikel.|
|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.009.png)|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.010.png)|
|Pada halaman Konselor di Admin, Admin dapat menambah dan mengedit data-data dari konselor.|Pada halaman Form Konsul di Admin, Admin bisa menambah dan mengedit isi form konsul.|
|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.011.png)|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.012.png)|
|Pada halaman pengajuan konseling ini admin bisa terima atau tolak pengajuan, jika terima maka akan langsung masuk ke Rekap Konseling jika ditolak tidak masuk Rekap Konseling.|Pada halaman Konseli Admin dapat melihat data konseli yang mengajukan konseling.|
|![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.013.png)||
|Pada halaman Rekap konseling ini Admin dapat menghapus data rekapan.||


### <a name="_xevmcg3w7t19"></a>**2.1.3 Antarmuka Perangkat Keras**
![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.014.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Pusat Informasi dan Konseling Konsultasi antara lain : 

1. PC / Laptop untuk menjalankan web ini admin membutuhkan sebuah PC yang menggunakan OS WIndows, Linux, atau MAC dan sudah terinstall browser.
### <a name="_19im02kqbffz"></a>**2.1.4 Antarmuka Perangkat Lunak**
Tidak ada 
### <a name="_s5tc8haz4nss"></a>**2.1.5 Antarmuka Komunikasi**
Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Pusat Informasi dan Konseling Konsultasi antara lain : 

1. Kabel Lan UTP RJ45
1. Modem
1. Wifi
### <a name="_2dg9h44ch3ey"></a>**2.1.6 Batasan Memori**
Tidak ada
### <a name="_jk777eczxovr"></a>**2.1.7 Operasi - Operasi**


|Operasi|Fungsi|
| :-: | :-: |
|Login|Digunakan untuk mengakses aplikasi|
|Input Data|Digunakan untuk memasukkan data-data|
|Kembali|Digunakan untuk kembali ke halaman sebelumnya|
|Hapus|Digunakan untuk menghapus data|
|Edit|Digunakan untuk mengubah data|
|View|Digunakan untuk menampilkan data|
|Simpan|Digunakan untuk menyimpan data |
|Cetak|Digunakan untuk mencetak laporan|

### <a name="_lwivq1d53awn"></a>**2.1.8 Kebutuhan Adaptasi**
Tidak ada
## <a name="_oj8qjq9qq7og"></a>**2.2 Spesifikasi Kebutuhan Fungsional**
![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.015.png)



### <a name="_7bty1ly1qdgd"></a><a name="_vrb91u97nfw9"></a>**2.2.1 Konseli Login**

Use Case : Login

Diagram :

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.016.png)

Deskripsi Singkat Konseli melakukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses atau gagal konseli dapat meminta kepada admin dibuatkan akunnya. Deskripsi langkah - langkah : 

1. Konseli melakukan login dengan memasukkan username dan password
1. Sistem melakukan validasi login
1. Bila sukses sistem akan mengarahkan ke halaman utama
1. Bila gagal sistem akan menampilkan pesan kesalahan dan menampilkan halaman login kembali

Xref : Bagian 3.2.1, Konseli Login
### <a name="_a7g461lguot1"></a>**2.2.2 Konseli Melihat Ketersediaan Konselor**

Use Case : Melihat Ketersediaan Konselor

Diagram : 

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.017.png)

Deskripsi Singkat Konseli dapat melihat ketersediaan konselor pada menu konselor.

Deskripsi langkah - langkah : 

1. Konseli mengklik menu konselor
1. Sistem akan menampilkan daftar konselor, nama, bidang beserta jadwal konselor

Xref : Bagian 3.2.2, Konseli Melihat Ketersedian Konselor



### <a name="_ado9vk4eg9rd"></a>**2.2.3 Konseli Mengisi Formulir Konseling**
Use Case : Mengisi Formulir Konseling

Diagram : 

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.018.png)

Deskripsi Singkat Konseli dapat mengisi formulir konseling.

Deskripsi langkah - langkah : 

1. Konseli mengklik menu form pengajuan
1. Sistem akan menampilkan halaman form pengajuan 
1. Konseli mengisi form pengajuan
1. Konseli akan dihubungi oleh admin jika pengajuan konsultasi diterima

Xref : Bagian 3.2.3, Konseli Mengisi Formulir Konseling
### <a name="_fd5vr0c0cl49"></a>**2.2.4 Admin Login**

Use Case : Login

Diagram : 

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.019.png)

Deskripsi Singkat Admin melakukan login terlebih dahulu sebelum masuk ke tampilan home dengan memasukkan username dan password, apabila login gagal maka sistem akan menampilkan pesan kesalahan / error.

Deskripsi langkah - langkah : 

1. Admin melakukan login dengan memasukkan username dan password
1. Sistem melakukan validasi login
1. Bila sukses sistem akan mengarahkan ke halaman utama
1. Bila gagal sistem akan menampilkan pesan kesalahan dan menampilkan halaman login kembali

Xref : Bagian 3.2.4, Admin Login
### <a name="_g3ixy0mv3r21"></a>**2.2.5 Admin Mengelola Rekap Konsultasi**
Use case : Mengelola Rekap Konsultasi

Diagram :

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.020.png)

Deskripsi Singkat Admin mengelola rekap konsultasi di dalam nya admin dapat menghapus rekap konsultasi.

Deskripsi langkah - langkah : 

1. Admin mengklik menu rekap konsultasi 
1. Sistem akan menampilkan halaman menu rekap konsultasi

Xref : Bagian 3.2.5, Admin Mengelola Data Konseli

### <a name="_pigwlncucvrd"></a>**2.2.6 Admin Mengelola Data Konseli**

Use Case : Mengelola Data Konseli

Diagram : 

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.021.png)

Deskripsi Singkat Admin mengelola data konseli didalam nya admin dapat menghapus, mengedit data konseli

Deskripsi langkah-langkah:

1. Admin mengklik menu konseli
1. Sistem akan menampilkan halaman menu konseli

Xref : Bagian 3.2.6, Admin Mengelola Data Konseli





### <a name="_c3b9tryy1gtx"></a>**2.2.7 Admin Mengelola Data Konselor**

Use Case : Mengelola Data Konselor

Diagram : 

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.022.png)

Deskripsi Singkat Admin mengelola data konselor, admin dapat menambahkan, menghapus, mengedit data konselor

Deskripsi langkah-langkah:

1. Admin mengklik menu konselor
1. Sistem akan menampilkan halaman menu konselor

Xref : Bagian 3.2.7, Admin Mengelola Data Konselor
### <a name="_t6nr47tgdg30"></a>**2.2.8 Admin Menerima Pengajuan Konseling**

Use Case : Mengkonfirmasi Pemakaian Konseling

Diagram : 

![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.023.png)Deskripsi Singkat Admin mengelola data pengajuan, admin dapat menambahkan, menghapus, mengedit data pengajuan

Deskripsi langkah-langkah:

1. Admin mengklik menu konsultasi
1. Sistem akan menampilkan halaman menu konsultasi

Xref : Bagian 3.2.8, Admin Menerima Pengajuan Konseling




## <a name="_iuods04ujgmk"></a>**2.3 Spesifikasi Kebutuhan Non-Fungsional**

- Tabel Kebutuhan Non-Fungsional


|No|Deskripsi|
| :-: | :- |
|1|Semua interface dan fungsi menggunakan Bahasa Indonesia|
|2|Perangkat Lunak dapat dipakai di semua platform OS ( Admin dan Konseli )|

## <a name="_5to0lhllmh2m"></a>**2.4 Karakteristik Pengguna**
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.
## <a name="_r6l58ug6oeit"></a>**2.5 Batasan - Batasan**
- Perangkat lunak web hanta dijalalnkan di windows (7,8,10).
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.
## <a name="_pulaf95cxl8d"></a>**2.6 Asumsi - Asumsi** 
Tidak ada
## <a name="_zf35m2nu62l6"></a>**2.7 Kebutuhan Penyeimbang**
Tidak ada
# <a name="_y5tu7k5ht78u"></a>**BAB III Requirement Specification**
## <a name="_nbu6mx46k0vh"></a>**3.1 Persyaratan Antarmuka Eksternal**
Salah satu cara mengakses aplikasi ini yaitu dengan membuat akun terlebih dahulu untuk yang belum mempunyai akun, login melalui aplikasi ini dengan mencantumkan username dan password kemudian sistem akan memvalidasi login. Setelah login berhasil sistem akan menampilkan halaman utama.



## <a name="_81cgir8y9qff"></a>**3.2 Functional Requirement**
Logika Struktur terdapat pada bagian 3.3.1
### <a name="_fpw4sz9f608q"></a>**3.2.1 Konseli Login**


|Nama Fungsi |Login|
| :- | :- |
|Xref|Bagian 2.2.1 Konseli Login|
|Trigger|Membuka web Pusat Informasi Konseling dan Konsultasi|
|Precondition |Halaman login|
|Basic Path |<p>1. Konseli melakukan login dengan memasukkan username dan password</p><p>2. Sistem melakukan validasi login</p><p>3. Bila sukses sistem akan mengarahkan ke halaman utama</p><p>4. Bila gagal sistem akan menampilkan pesan kesalahan dan menampilkan halaman login kembali</p>|
|Alternatif|Tidak ada|
|Post Condition|Konseli dapat login dan mengakses website Pusat Informasi Konseling dan Konsultasi|
|Exception Push|Username dan password salah|
####
### <a name="_x2fbxbhz9cyf"></a><a name="_4w5e0uewgxsc"></a>**3.2.2 Konseli Melihat Ketersediaan Konselor**


|Nama Fungsi |Melihat ketersediaan konselor|
| :- | :- |
|Xref|Bagian 2.2.2 Konseli Melihat Ketersediaan Konselor|
|Trigger|Konseli menekan menu konselor|
|Precondition |Halaman Utama Konseli|
|Basic Path |<p>1. Konseli mengklik menu konselor</p><p>2. Sistem akan menampilkan daftar konselor, nama, bidang beserta jadwal konselor</p>|
|Alternatif|Tidak ada|
|Post Condition|Halaman menu konselor|
|Exception Push|Tidak ada|

### <a name="_7jdpvsy4zihc"></a>**3.2.3 Konseli Mengisi Formulir Konseling**


|Nama Fungsi |Mengisi formulir Konseling|
| :- | :- |
|Xref|Bagian 2.2.3 Konseli Mengisi Formulir Konseling|
|Trigger|Konseli menekan menu Form Konseling|
|Precondition |Halaman Utama Konseli|
|Basic Path |<p>1. Konseli mengklik menu form pengajuan</p><p>2. Sistem akan menampilkan halaman form pengajuan </p><p>3. Konseli mengisi form pengajuan</p>|
|Alternatif|Tidak ada|
|Post Condition|Konseli dapat melakukan konseling sesuai jadwal dan lokasi yang sudah disepakati|
|Exception Push|Tidak ada|
### <a name="_so5z9vbz9axd"></a><a name="_h033r1crinn0"></a>**3.2.4 Admin Login**

|Nama Fungsi |Login |
| :- | :- |
|Xref|Bagian 2.2.4 Admin Login|
|Trigger|Membuka web Pusat Informasi Konseling dan Konsultasi|
|Precondition |Halaman login|
|Basic Path |<p>1. Admin melakukan login dengan memasukkan username dan password</p><p>2. Sistem melakukan validasi login</p><p>3. Bila sukses sistem akan mengarahkan ke halaman utama</p><p>4. Bila gagal sistem akan menampilkan pesan kesalahan dan menampilkan halaman login kembali</p>|
|Alternatif|Tidak ada|
|Post Condition|Admin dapat login dan mengakses website Pusat Informasi Konseling dan Konsultasi|
|Exception Push|Username dan password salah|


### <a name="_ywlqzi5y1d83"></a><a name="_e0h4uzldzkyc"></a>**3.2.5 Admin Mengelola Rekap Konsultasi**


|Nama Fungsi |Mengelola rekap konsultasi|
| :- | :- |
|Xref|Bagian 2.2.5 Admin Mengelola Rekap Konsultasi|
|Trigger|Admin menekan menu Rekap Konsultasi|
|Precondition |Halaman Utama Admin|
|Basic Path |<p>1. Admin mengklik menu rekap konsultasi </p><p>2. Sistem akan menampilkan halaman menu rekap konsultasi</p>|
|Alternatif|Tidak ada |
|Post Condition|Halaman Rekap Konsultasi|
|Exception Push|Tidak ada|

### <a name="_wnu8zggsn9uy"></a>**3.2.6 Admin Mengelola Data Konseli**


|Nama Fungsi |Mengelola Data Konseli|
| :- | :- |
|Xref|Bagian 2.2.6 Admin Mengelola Data Konseli|
|Trigger|Admin menekan menu Konseli|
|Precondition |Halaman Utama Admin|
|Basic Path |<p>1. Admin mengklik menu konseli</p><p>2. Sistem akan menampilkan halaman menu konseli</p>|
|Alternatif|Tidak ada |
|Post Condition|Halaman Konseli|
|Exception Push|Tidak ada |

### <a name="_pmvl0nas00nz"></a>**3.2.7 Admin Mengelola Data Konselor**


|Nama Fungsi |Mengelola data konselor|
| :- | :- |
|Xref|Bagian 2.2.7 Admin Mengelola Data Konselor|
|Trigger|Admin menekan menu Konselor|
|Precondition |Halaman Utama Admin|
|Basic Path |<p>1. Admin mengklik menu konselor</p><p>2. Sistem akan menampilkan halaman menu konselor</p>|
|Alternatif|Tidak ada|
|Post Condition|Halaman Konselor|
|Exception Push|Tidak ada|

### <a name="_tz472t2ot5b4"></a>**3.2.8 Admin Menerima Pengajuan Konseling**


|Nama Fungsi |Mengkonfirmasi pemakaian konseling|
| :- | :- |
|Xref|Bagian 2.2.8 Admin Mengkonfirmasi Pemakai Konseling|
|Trigger|Admin menekan menu Pengajuan Konseling|
|Precondition |Halaman Utama Admin|
|Basic Path |<p>1. Admin mengklik menu konsultasi</p><p>2. Sistem akan menampilkan halaman menu konsultasi</p>|
|Alternatif|Tidak ada|
|Post Condition|Halaman Pengajuan Konseling|
|Exception Push|Tidak ada|
## <a name="_146u2jbn8sl4"></a>**3.3 Struktur Detail Kebutuhan Non-Fungsional**
### <a name="_jf9rlztbut4k"></a>**3.3.1 Logika Struktur Data**
![](Aspose.Words.1832e7e0-ea33-4562-8825-714f4ec16199.024.png)

### <a name="_n0jpluqc273p"></a><a name="_uqs7kq2fqkt3"></a>**Tabel User**

|Data Item|Type|Deskripsi|
| :- | :- | :- |
|id|char|Nomor auto increment id|
|nama|varchar|Berisikan nama dari user|
|password|varchar|Berisikan password user untuk login|
|role|varchar||
|email|varchar|Berisikan email user untuk login|
|no\_hp|varchar|Berisikan nomor hp user|
### <a name="_y95jd4nyd4o"></a>**Tabel Konselor**

|Data Item|Type|Deskripsi|
| :- | :- | :- |
|nama\_konselor|varchar|Berisikan nama dari konselor|
|id\_konselor|char|Nomor auto increment id\_konselor|
|status\_konselor|varchar|Berisikan status konselor|
|bidang|varchar|Berisikan bidang untuk konsultasi yang ingin lebih berfokus pada suatu bidang|
|id|char|Nomor auto increment id|
### <a name="_kutinjs7ul3"></a>**Tabel Ajukan**

|Data Item|Type|Deskripsi|
| :- | :- | :- |
|id\_konselor|char|Nomor auto increment id\_konselor|
|id\_konseling|char|Nomor auto increment id\_konseling|
|id\_lokasi|char|Nomor auto increment id\_lokasi|
|id\_konseli|char|Nomor auto increment id\_konseli|
|waktu|time|Berisikan waktu pemakaian konsultasi|
|tanggal|date|Berisikan tanggal pemakaian  konsultasi|

# <a name="_hd6nk2906iq6"></a>**Pembagian Tugas Kelompok**
Abdul Habib Risyik : Use Case dan ERD

Muhammad Amien Rais : Figma dan SRS

Muhammad Farel Wicaksono : Figma dan SRS

Muhammad Rizki : Figma dan SRS
