# 📈 Week 9: Advanced Tableau - Calculation & LOD Expressions

## 📌 Deskripsi
Minggu ini berfokus pada teknik perhitungan lanjutan di Tableau untuk menghasilkan analisis yang lebih mendalam dan dinamis. Saya mempelajari cara menggunakan *Table Calculations* dan *Level of Detail (LOD)* untuk membandingkan performa data di berbagai level dimensi.

## 🛠️ Teknik Analisis & Visualisasi
- **Cumulative Sales (Running Total):** Membuat *calculated field* menggunakan fungsi `RUNNING_SUM(SUM([Sales]))` untuk memantau pertumbuhan total penjualan seluruh toko dari bulan ke bulan.
- **LOD Expression (EXCLUDE):** Menggunakan fungsi `{ EXCLUDE [Region]: AVG([Sales]) }` untuk menghitung rata-rata penjualan nasional sebagai pembanding terhadap rata-rata penjualan di setiap wilayah (Region).
- **Growth Analysis:** Menganalisis tren peningkatan penjualan dan mengidentifikasi bulan-bulan tertentu di mana terjadi penurunan performa meskipun tren kumulatif meningkat.

## 💡 Key Insights
- **Tren Penjualan:** Penjualan menunjukkan peningkatan kumulatif yang stabil hingga mencapai angka di atas 140M pada awal 2024.
- **Analisis Wilayah:** Dengan fungsi EXCLUDE, saya bisa melihat wilayah mana yang performanya di atas rata-rata nasional dan wilayah mana yang perlu perhatian khusus.

## 📁 Dokumentasi
<img width="930" height="528" alt="image" src="https://github.com/user-attachments/assets/d3bb0aee-ebac-4d1d-9dba-ef5656b9e3ec" />
<img width="1003" height="591" alt="image" src="https://github.com/user-attachments/assets/b8ec1b01-77ca-4827-80d1-8058d83c421e" />
