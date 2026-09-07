# 📊 Customer Cohort & Retention Analysis

## 📌 Business Overview
Dalam industri e-commerce dan retail, mempertahankan pelanggan (*customer retention*) jauh lebih efisien dibandingkan terus-menerus mencari pelanggan baru. Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan waktu transaksi pertama mereka (*cohort*) dan menganalisis pola retensi serta perilaku pembelian dari waktu ke waktu.

---

## 🎯 Project Objectives
* **Mengidentifikasi Pola Retensi:** Mengetahui berapa persentase pelanggan yang kembali melakukan transaksi setelah bulan pertama.
* **Evaluasi Perilaku Pelanggan:** Menganalisis perbedaan aktivitas pembelian antar *cohort* bulanan.
* **Rekomendasi Bisnis:** Memberikan wawasan berbasis data untuk mendukung strategi *marketing* dan *customer engagement*.

---

## 🛠️ Tools & Technologies
* **Python 3.x**
* **Google Colab** (Environment)
* **Pandas & NumPy** (Data Cleaning & Manipulation)
* **Seaborn & Matplotlib** (Data Visualization & Heatmap)

---

## 📈 Methodology
1. **Data Preprocessing:**
   * Cleaning data dari transaksi *missing values* atau nilai negatif (pembatalan/retur).
   * Menentukan *Cohort Month* (bulan transaksi pertama pelanggan) dan *Transaction Month*.
2. **Cohort Calculation:**
   * Menghitung rentang bulan (*cohort index*) antara transaksi pertama dengan transaksi berikutnya.
   * Membuat *Cohort Matrix* berdasarkan jumlah pelanggan aktif (*active users*).
3. **Retention Rate Analysis:**
   * Membagi jumlah pelanggan aktif di bulan ke-$n$ dengan total pelanggan awal di bulan pertama untuk mendapatkan persentase retensi.
   * Visualisasi menggunakan *Heatmap*.

---

## 💡 Key Insights & Findings
* **Persentase Retensi Awal:** Menunjukkan penurunan terbesar terjadi pada bulan pertama setelah pembelian pertama (*Month 1 drop-off*).
* **Perilaku Cohort Tertentu:** Cohort bulan-bulan tertentu menunjukkan tingkat retensi lebih tinggi yang dipengaruhi oleh tren musiman atau promosi khusus.

---

## 🚀 How to Run
Anda dapat menjalankan dan mencoba ulang kode notebook ini secara langsung melalui Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rezha9876/Portofolio-Data-Analyst/blob/main/cohort-analysis/Cohort_Analysis.ipynb)
