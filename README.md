# Analisis Sentimen Aplikasi by.U di Google Play Store

## 📌 Deskripsi
Proyek ini bertujuan untuk menganalisis sentimen ulasan pengguna terhadap aplikasi by.U yang tersedia di Google Play Store. Dengan menggunakan teknik pemrosesan bahasa alami (NLP) dan pembelajaran mesin (machine learning), proyek ini mengkategorikan ulasan pengguna ke dalam sentimen positif, negatif, atau netral.

## 🎯 Fitur Utama
- Pengambilan data ulasan aplikasi by.U dari Google Play Store
- Pra-pemrosesan data (cleaning, tokenization, stopword removal, stemming, lemmatization)
- Analisis sentimen menggunakan model machine learning berbasis Naïve Bayes dan Random Forest
- Visualisasi data menggunakan Matplotlib dan Seaborn
- Word Cloud untuk analisis kata yang sering muncul dalam ulasan

## 📂 Struktur Proyek
```
📁 AnalisisSentimenByU
│── 📄 AnalisisSentimenByU.ipynb  # Notebook utama
│── 📄 evaluasi_aplikasi.csv      # Data hasil scraping
│── 📄 README.md                 # Dokumentasi proyek
```

## ⚙️ Cara Menjalankan Proyek
### 1️⃣ Prasyarat
Pastikan Anda telah menginstal Python serta pustaka yang diperlukan:
```bash
pip install pandas numpy seaborn scikit-learn nltk wordcloud matplotlib
```

### 2️⃣ Jalankan Notebook
Buka Jupyter Notebook dan jalankan `AnalisisSentimenByU.ipynb` untuk melihat hasil analisis secara langsung.
```bash
jupyter notebook AnalisisSentimenByU.ipynb
```

## 📊 Hasil Analisis
Hasil analisis meliputi:
- Distribusi sentimen positif, negatif, dan netral dalam ulasan pengguna
- Word cloud dari kata-kata paling sering digunakan dalam ulasan
- Grafik tren sentimen dari waktu ke waktu
- Evaluasi model menggunakan metrik akurasi, precision, recall, dan F1-score


🚀 **Semoga bermanfaat!**

