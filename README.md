# ADUIN - Analisis Digital Untuk Insight Nusantara (Data Science Repository)

> *"Aduin aja, biar AI yang urus"*

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://guswid715-aduin-capstone-project-dataset-app-z4epkh.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)

Repositori ini difokuskan pada pemrosesan data (Data Wrangling), rekayasa fitur (Feature Engineering), dan Exploratory Data Analysis (EDA) untuk proyek **ADUIN**, sebuah platform klasifikasi pengaduan masyarakat berbasis AI. Proyek ini dikembangkan untuk Capstone Project DBS Foundation Coding Camp 2026 oleh Tim CC26-PSU299.

## 📊 Live Dashboard
Hasil Exploratory Data Analysis (EDA) interaktif dapat diakses melalui Streamlit Cloud:
👉 **[Buka Dashboard EDA ADUIN](https://guswid715-aduin-capstone-project-dataset-app-z4epkh.streamlit.app/)**

---

## 🎯 Fokus Utama Repositori
Repositori ini merepresentasikan tahap awal dari *pipeline* AI ADUIN, yang meliputi:
1. **Data Wrangling End-to-End:** - Pembersihan *noise* (URL, mention, hashtag, karakter non-ASCII).
   - Normalisasi teks informal (*slang*, *typo*) dari Twitter/X menjadi bahasa baku.
   - Penyatuan sumber data media sosial (Twitter/X) dan portal berita (Kaggle).
2. **Feature Engineering:**
   - Pembuatan target *Multi-label* untuk 10 Kategori Isu Publik (Infrastruktur, Lingkungan, dll).
   - Penentuan target *Single-label* untuk tingkat Urgensi dan Sentimen menggunakan metode *Keyword Scoring* & *Pessimistic Priority*.
3. **Data Splitting (Stratified):**
   - Pemisahan dataset menjadi Train (80%) dan Test (20%) secara proporsional untuk 10 label kategori menggunakan `iterative-stratification`.
4. **Exploratory Data Analysis (EDA):**
   - Menjawab pertanyaan bisnis terkait distribusi isu teratas, urgensi, dan korelasi sentimen publik.

---

## 🛠️ Tech Stack & Library
- **Bahasa:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning & Splitting:** Scikit-Learn, Iterative-Stratification
- **Data Visualization:** Matplotlib, Seaborn
- **Dashboarding:** Streamlit

---

## 🚀 Cara Menjalankan Dashboard Secara Lokal

Jika Anda ingin menjalankan dashboard EDA ini di komputer lokal, ikuti langkah berikut:

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/guswid715/aduin-capstone-project-dataset.git](https://github.com/guswid715/aduin-capstone-project-dataset.git)
   cd aduin-capstone-project-dataset
   ```
2. **Instal dependensi:**
```bash
   pip install -r requirements.txt
```
3. **Jalankan Streamlit:**
```bash
   streamlit run app.py
```

---

## 👥 Tim CC26-PSU299

Repositori data ini dikelola oleh tim Data Science:

1. Ida Bagus Gede Widiastana Bawaskara - Data Scientist
2. Diana Qisthin Thoniyah - Data Scientist
