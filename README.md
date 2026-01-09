
# 🛒 Analisis Faktor Pendorong Pembelian Impulsif di TikTok Shop

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue&logo=python&logoColor=white)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans%20%26%20Regression-orange)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

> **Proyek Akhir Fundamental Data Analysis (FDA)**
> Studi kuantitatif mengenai perilaku konsumen Gen-Z dalam melakukan *Impulse Buying* di platform *Social Commerce*.

---

## 📖 Latar Belakang

Fenomena *Live Shopping* dan promosi kilat di TikTok Shop telah mengubah pola belanja mahasiswa. Proyek ini bertujuan untuk menjawab pertanyaan bisnis: **"Faktor psikologis apa yang paling kuat mendorong seseorang untuk membeli secara impulsif?"**

Kami menggunakan pendekatan berbasis data untuk membantu tim pemasaran mengalokasikan anggaran promosi secara efektif demi mencapai ROI (*Return on Investment*) maksimal.

---

## 🎯 Tujuan Analisis

1.  **Kuantifikasi Dampak:** Mengukur seberapa besar pengaruh faktor psikologis (*Trust, Scarcity, Hedonic, dll.*) terhadap keputusan pembelian impulsif.
2.  **Segmentasi Peluang:** Mengelompokkan konsumen ke dalam klaster perilaku untuk penargetan iklan yang presisi.
3.  **Rekomendasi Strategis:** Memberikan *actionable insights* bagi *seller* TikTok Shop.

---

## 🛠️ Metodologi & Teknlogi

Proyek ini menggunakan metodologi **CRISP-DM** (*Cross-Industry Standard Process for Data Mining*) dengan rincian teknis:

| Tahapan | Metode / Algoritma | Deskripsi |
| :--- | :--- | :--- |
| **Preprocessing** | Feature Engineering | Agregasi skor Likert & Standard Scaling (Z-Score) |
| **Modelling 1** | **K-Means Clustering** | Segmentasi konsumen menjadi 3 profil perilaku |
| **Modelling 2** | **Multiple Linear Regression** | Mengukur koefisien dampak ($\beta$) antar variabel |
| **Evaluasi** | R-Squared ($R^2$) | Validasi kekuatan model prediksi (Hasil: 0.4775) |

**Tools:** Python (Pandas, Scikit-Learn, Matplotlib/Seaborn).

---

## 📊 Temuan Utama (Key Insights)

### 1. Faktor Pendorong Terkuat
Berdasarkan analisis regresi, faktor **Shopping Lifestyle & Sales Promotion (SL)** memiliki dampak terbesar ($\beta = 0.2391$), diikuti oleh **Trust (TR)** dan **Hedonic Motivation (HM)**.

### 2. Segmentasi Konsumen
Ditemukan 3 tipe pembeli:
*   **🔴 Cluster 1 (High-Impulse Buyers):** Sangat mudah terpicu oleh diskon & urgensi. Dominasi wanita (62%) dengan pendapatan menengah. -> *Target Utama!*
*   **🟡 Cluster 0 (Discovery-Driven):** Suka melihat-lihat visual produk.
*   **🔵 Cluster 2 (Skeptical Buyers):** Sulit dipengaruhi, tingkat kepercayaan rendah.

---

## 💡 Rekomendasi Bisnis

1.  **Alokasi Budget:** Prioritaskan anggaran marketing untuk **Flash Sale** & **Gratis Ongkir** (Lifestyle factor), karena ini pemicu terkuat.
2.  **Strategi Konten:** Gunakan narasi *"Self-Reward"* atau *"Retail Therapy"* dalam *Live Streaming* untuk menyentuh sisi Hedonis konsumen.
3.  **Targeting Iklan:** Fokuskan iklan berbayar (*TikTok Ads*) pada segmen Wanita usia mahasiswa dengan minat pada konten gaya hidup.

---

## 👥 Tim Peneliti

Mahasiswa Program Studi Sistem Informasi, Universitas Bina Sarana Informatika (Kampus Pontianak).

*   **Jaenal Arifin** (19240216)
*   **Erwin Gouw** (19240336)
*   **Afriza** (19240293)

---
*Dibuat sebagai syarat kelulusan mata kuliah Fundamental Data Analysis (2025)*
```
