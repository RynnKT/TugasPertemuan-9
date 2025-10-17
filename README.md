
---

# 📘 Pemrograman Berorientasi Objek – Pertemuan 9

### Proyek Integrasi iReport dengan NetBeans

## 🧩 Deskripsi

Proyek ini dibuat untuk memenuhi tugas mata kuliah **Pemrograman Berorientasi Objek (PBO 1)** di Universitas Islam Negeri Sunan Ampel Surabaya.
Fokus utama proyek ini adalah **pembuatan laporan menggunakan iReport** dan **integrasinya dengan NetBeans**, yang dijalankan pada **JDK versi 20 ke atas**.

Implementasi proyek mencakup beberapa tahap utama:

* **Instalasi iReport** → Mengunduh dan menginstal iReport versi terbaru agar kompatibel dengan JDK 20+.
* **Integrasi dengan NetBeans** → Menghubungkan iReport ke dalam proyek Java untuk menjalankan laporan langsung dari IDE.
* **Pembuatan Laporan** → Mendesain laporan dengan format tabel, grafik, dan parameter dinamis.
* **Koneksi Database** → Menghubungkan laporan dengan database **PostgreSQL** untuk menampilkan data secara real-time.
* **Pengujian Laporan** → Menjalankan dan memvalidasi laporan agar tampil sesuai desain dan parameter yang diinput.

---

## 🎯 Tujuan

* Memahami langkah-langkah instalasi dan konfigurasi iReport agar kompatibel dengan JDK 20 ke atas.
* Mengintegrasikan iReport dengan proyek Java di NetBeans.
* Melatih pembuatan laporan dinamis dan interaktif menggunakan parameter dan subreport.
* Menghubungkan laporan dengan database PostgreSQL secara langsung.
* Mengembangkan keterampilan dalam menyajikan data profesional melalui Java dan iReport.

---

## ⚙️ Langkah Pengerjaan

### 1. Instalasi Plugin iReport di NetBeans

1. Buka menu **Tools → Plugins → Downloaded → Add Plugins**.
2. Tambahkan 5 file plugin (termasuk `jdesktop layout`).
3. Setelah instalasi, **restart NetBeans** agar perubahan diterapkan.

### 2. Integrasi iReport ke Proyek

1. Buka proyek Java yang telah dibuat sebelumnya (misalnya `Pertemuan9`).
2. Tambahkan library `jar` yang diperlukan untuk kompatibilitas dengan NetBeans.
3. Buat file baru: **New File → Report → Report Wizard**.
4. Pilih layout, beri nama (misalnya `DataPramuka`), dan lanjutkan.

### 3. Koneksi ke Database

1. Klik **New Connection** → pilih `NetBeans Database JDBC Connection`.
2. Isi konfigurasi koneksi sesuai database PostgreSQL.
3. Uji koneksi dengan tombol **Test**, kemudian **Save** jika berhasil.

### 4. Membuat Query dan Desain Laporan

1. Masukkan query SQL untuk menampilkan data.
2. Pindahkan semua field yang dibutuhkan, lalu klik **Next → Finish**.
3. Desain laporan menggunakan layout pilihan.
4. Klik **Preview** untuk meng-compile file `.jrxml` menjadi `.jasper`.

### 5. Menambahkan Fungsi Cetak Laporan

1. Tambahkan library iReport pada source code `DataPramuka.java`.
2. Pada tombol **Cetak**, tambahkan kode untuk mencetak laporan menjadi **PDF**.

---

## 🧾 Output

Hasil akhir dari proyek ini adalah **laporan data yang dapat dicetak dalam format PDF** dan menampilkan data langsung dari database PostgreSQL melalui NetBeans.

---

