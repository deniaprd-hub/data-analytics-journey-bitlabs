# 🧠 Week 5: Advanced SQL & Business Problem Solving

## 📌 Deskripsi
Minggu ini merupakan perpaduan antara analisis strategi bisnis dan teknik SQL tingkat lanjut. Saya mempelajari cara membedah masalah kompleks menggunakan framework terstruktur dan mengambil data performa yang lebih mendalam dari database.

## 📈 Analisis Bisnis: The Problem Tree
Saya melakukan analisis terhadap masalah **"Keterlambatan Pengiriman Trafo Swasta Non-Standar"**.
- **Root Cause (Penyebab):** Desain spek yang rumit, material khusus yang harus impor (lead time 2 bulan), dan kesalahan produksi (*human error*).
- **Impact (Dampak):** Penurunan kepercayaan pelanggan dan pembengkakan biaya operasional karena pengerjaan ulang.
- **Solusi:** Digitalisasi pemantauan stok material khusus dan standarisasi desain untuk spek yang sering dipesan.

## 🛠️ Teknik SQL Lanjutan (Window Functions)
Saya mempraktikkan kueri untuk analisis tren dan peringkat:
- **Ranking:** Menggunakan `RANK()` dan `DENSE_RANK()` untuk melihat peringkat penjualan per genre musik.
- **Cumulative Sales:** Menggunakan fungsi `SUM() OVER (PARTITION BY ...)` untuk menghitung total penjualan kumulatif per genre berdasarkan tanggal faktur.
- **Logika JOIN:** Menggabungkan lebih dari 4 tabel (`InvoiceLine`, `Track`, `Genre`, dan `Invoice`) untuk mendapatkan laporan penjualan yang komprehensif.

## 📁 Dokumentasi
<img width="570" height="180" alt="image" src="https://github.com/user-attachments/assets/c9750ad4-6d7a-42be-8ec1-9ce7f08f6af6" />
