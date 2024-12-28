Deskripsi:
Proyek ini bertujuan untuk mengumpulkan, mengolah, dan menganalisis dataset tentang kejahatan di Chicago dari tahun 2018 hingga 2023. Data ini akan digunakan untuk membangun sistem Data Warehouse (DW) dan Data Mart (DM) yang dapat memberikan informasi yang berguna dan wawasan mendalam terkait pola dan tren kejahatan di Chicago.


Struktur Data
Dataset kejahatan Chicago yang digunakan mencakup informasi berikut:

- ID: Nomor unik untuk setiap kejadian kejahatan.
- Case Number: Nomor kasus yang diberikan oleh polisi.
- Date: Tanggal dan waktu kejadian.
- Block: Lokasi blok tempat kejadian.
- IUCR: Kode yang mengidentifikasi jenis kejahatan.
- Primary Type: Kategori utama dari kejahatan.
- Description: Deskripsi singkat tentang kejahatan.
- Location Description: Deskripsi lokasi kejadian.
- Arrest: Apakah ada penangkapan yang dilakukan (true/false).
- Domestic: Apakah kejadian tersebut terkait dengan kekerasan domestik (true/false).
- Beat: Area kecil untuk keperluan patroli.
- District: Distrik polisi.
- Ward: Wilayah pemerintahan kota.
- Community Area: Area komunitas di Chicago.
- FBI Code: Kode FBI yang mengklasifikasikan kejahatan.
- X Coordinate: Koordinat X (geografis).
- Y Coordinate: Koordinat Y (geografis).
- Year: Tahun kejadian.
- Updated On: Tanggal terakhir data diperbarui.
- Latitude: Lintang geografis.
- Longitude: Bujur geografis.
- Location: Koordinat geografis (gabungan Lintang dan Bujur).


Langkah-langkah Menjalankan Proyek

- Persiapan Data:
  * Unduh dataset kejahatan Chicago dari Chicago Data Portal.
  * Simpan dataset dalam format CSV di direktori proyek.

- Proses ETL (Extract, Transform, Load):
  * Ekstraksi data dari file CSV.
  * Transformasi data untuk membersihkan dan mempersiapkan data agar sesuai dengan skema DW.
  * Muat data ke dalam Data Warehouse.

- Membangun Data Warehouse:
  * Buat skema Data Warehouse menggunakan model bintang (star schema) yang mencakup tabel fakta dan dimensi.
  * Tabel Fakta: Menyimpan data kejadian kejahatan.
  * Tabel Dimensi: Menyimpan informasi terkait dimensi waktu, lokasi, jenis kejahatan, dll.

- Membangun Data Mart:
  * Identifikasi kebutuhan analisis khusus dan buat Data Mart sesuai kebutuhan.
  * Contoh: Data Mart untuk analisis jenis kejahatan, waktu kejadian, dll.

- Analisis dan Visualisasi:
  * Gunakan tools analisis data (seperti Python, R, atau SQL) untuk menganalisis data dalam DW/DM.
  * Buat visualisasi data menggunakan alat visualisasi (seperti Tableau, Power BI, atau matplotlib).


Alat dan Teknologi yang Digunakan
- Database Management System (DBMS): MySQL.
- Alat Visualisasi: Microsoft Excel.
- ETL Tools: Pentaho Data Integration (PDI).

Notes: Desain DW/DM ada di dalam Jurnal.
