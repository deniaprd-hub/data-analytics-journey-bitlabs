# 🏨 Midterm Project: Hotel Booking Demand Analysis

## 📌 Situation & Task
Proyek ini menganalisis dataset reservasi hotel untuk memahami pola pembatalan (*cancellation*). Fokus utamanya adalah mengidentifikasi faktor apa saja yang menyebabkan tamu membatalkan pesanan dan memberikan rekomendasi strategis untuk menurunkan tingkat pembatalan di City Hotel dan Resort Hotel.
<img width="707" height="400" alt="image" src="https://github.com/user-attachments/assets/7047a1fa-849a-436c-9cb2-94f5cbf916d3" />


## 🛠️ Tech Stack
- **SQL:** Untuk ekstraksi data dan filter kondisi tertentu.
- **Python (Pandas, Seaborn, Matplotlib):** Untuk pembersihan data, pengolahan statistik, dan visualisasi tren.
- **Business Framework:** Root Cause Analysis (Problem Tree).

## 📊 Langkah Kerja & Analisis
1. **Data Cleaning:** Menangani data kosong (Missing Values) pada kolom `agent` dan `company`.
2. **Exploratory Data Analysis (EDA):**
   - Menemukan bahwa **City Hotel** memiliki tingkat pembatalan lebih tinggi dibandingkan Resort Hotel.
   - Menganalisis korelasi antara *Lead Time* (jarak waktu pesan ke hari-H) dengan kemungkinan batal.
3. **Hypothesis Testing:** Menguji apakah permintaan khusus (*Special Requests*) berpengaruh pada pembatalan.
<img width="324" height="431" alt="image" src="https://github.com/user-attachments/assets/cf28941c-7c7a-4f5d-8643-85711bbeba87" />

## 💡 Key Insights & Recommendations
- **Insights:** Tamu yang tidak memberikan permintaan khusus memiliki kemungkinan pembatalan yang jauh lebih tinggi. Tingginya *lead time* juga berbanding lurus dengan risiko pembatalan.
- **Recommendation:** Memberikan promo "Non-Refundable" untuk pemesanan dengan *lead time* di atas 30 hari dan meningkatkan keterlibatan pelanggan yang tidak memiliki permintaan khusus melalui email konfirmasi otomatis.
<img width="772" height="455" alt="image" src="https://github.com/user-attachments/assets/02093af5-11b5-42d0-8a27-1858d4e0efc8" />
<img width="397" height="356" alt="image" src="https://github.com/user-attachments/assets/a1f9f5ca-816d-46ed-b813-1cef3c35448f" />

