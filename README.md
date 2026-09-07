#  Customer Cohort & Retention Analysis

## Business Overview

Dalam bisnis e-commerce dan retail, mempertahankan pelanggan yang sudah pernah bertransaksi sering kali lebih efektif daripada terus mencari pelanggan baru. Melalui project ini, saya menganalisis perilaku pelanggan menggunakan **cohort analysis** untuk melihat seberapa banyak pelanggan kembali melakukan pembelian setelah transaksi pertama mereka.

## Project Objectives

Project ini bertujuan untuk:

- Menganalisis tingkat **customer retention** dari bulan ke bulan.
- Membandingkan pola pembelian antar **cohort** berdasarkan bulan transaksi pertama pelanggan.
- Memberikan insight yang dapat digunakan untuk mendukung strategi pemasaran dan meningkatkan loyalitas pelanggan.

## Tools & Technologies

- **Python 3**
- **Google Colab**
- **Pandas & NumPy** untuk proses data cleaning dan analisis.
- **Matplotlib & Seaborn** untuk visualisasi data dan pembuatan heatmap.

## Methodology

1. **Data Preprocessing**
   - Membersihkan data transaksi, termasuk menghapus data yang tidak valid seperti nilai kosong, retur, atau pembatalan transaksi.
   - Menentukan **Cohort Month** (bulan transaksi pertama pelanggan) dan **Transaction Month**.

2. **Cohort Analysis**
   - Menghitung selisih bulan antara transaksi pertama dan transaksi berikutnya untuk setiap pelanggan.
   - Menyusun **cohort matrix** berdasarkan jumlah pelanggan yang masih aktif di setiap periode.

3. **Retention Rate**
   - Menghitung persentase pelanggan yang kembali bertransaksi pada bulan ke-*n* dibandingkan dengan jumlah pelanggan pada bulan pertama.
   - Menampilkan hasil analisis dalam bentuk **heatmap** agar pola retensi lebih mudah dibaca.

## Key Insights

Beberapa temuan utama dari analisis ini:

- Tingkat retensi mengalami penurunan paling besar setelah bulan pertama sejak pelanggan melakukan pembelian pertama.
- Beberapa cohort memiliki retensi yang lebih baik dibandingkan cohort lainnya, yang kemungkinan dipengaruhi oleh periode promosi atau faktor musiman.

---

Notebook ini dapat dijalankan langsung melalui Google Colab untuk melihat proses analisis dan visualisasi secara lengkap.

**Open in Google Colab**  
https://colab.research.google.com/github/Rezha9876/Portofolio-Data-Analyst/blob/main/cohort-analysis/Cohort_Analysis.ipynb
