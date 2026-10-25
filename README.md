# 🏙️ Jakarta Urban Air Quality & Mobility Analysis

> An end-to-end data analytics project examining the relationship between air pollution (PM2.5 / PM10), extreme weather events, and urban mobility patterns across DKI Jakarta.

---

## 📌 Executive Summary
*(Draft - Akan dilengkapi seiring analisis berjalan)*

Proyek ini bertujuan untuk menganalisis bagaimana fluktuasi kualitas udara (khususnya partikel halus PM2.5 dan PM10) serta kondisi cuaca (suhu dan curah hujan ekstrem) mempengaruhi dinamika aktivitas dan mobilitas warga di DKI Jakarta. Analisis ini ditujukan untuk memberikan rekomendasi berbasis data bagi pengelola transportasi publik dan pembuat kebijakan tata kota.

---

## 🎯 Business Problem & Key Questions
1. **Pola Temporal Polusi**: Pada jam dan hari apa tingkat polusi udara mencapai titik tertinggi di Jakarta?
2. **Korelasi Cuaca**: Bagaimana pengaruh musim kemarau vs musim hujan terhadap dispersi partikel polutan?
3. **Dampak terhadap Mobilitas**: Apakah hari-hari dengan kualitas udara kategori "Sangat Tidak Sehat" menurunkan volume mobilitas publik atau memicu pergeseran moda transportasi?
4. **Actionable Recommendations**: Strategi apa yang dapat diimplementasikan oleh pemangku kepentingan untuk mengantisipasi lonjakan polusi?

---

## 🛠️ Tech Stack & Architecture
- **Language**: Python (pandas, numpy, requests, matplotlib, seaborn)
- **Data Sourcing**: Open-Meteo Historical Weather & Air Quality API, Public Mobility Datasets
- **Database / Transformation**: SQL / DuckDB / pandas
- **Visualization & Reporting**: Power BI / Tableau / Jupyter Notebook

---

## 📂 Project Structure
```text
urban-air-mobility-analysis/
├── data/
│   ├── raw/             # Data mentah dari API
│   └── processed/       # Data bersih hasil pembersihan & agregasi
├── notebooks/           # Jupyter Notebooks untuk ETL dan Analisis (EDA)
├── .gitignore           # File konfigurasi abaikan file data besar
└── README.md            # Dokumentasi proyek portofolio
```

---

## 🚀 Status Proyek
- [x] Inisialisasi struktur repositori & scoping masalah
- [ ] Pengambilan data cuaca & kualitas udara Jakarta (Open-Meteo API)
- [ ] Penggabungan & pembersihan dataset (ETL)
- [ ] Exploratory Data Analysis (EDA) & pengujian hipotesis
- [ ] Dashboard interaktif & penulisan rekomendasi bisnis
