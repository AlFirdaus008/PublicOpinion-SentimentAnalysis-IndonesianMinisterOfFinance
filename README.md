# Public Opinion Analysis: New Minister of Finance Indonesia 🇮🇩📊
Proyek ini merupakan implementasi Integrated AI Approach untuk menganalisis sentimen dan opini publik masyarakat Indonesia di platform YouTube terkait penunjukan Menteri Keuangan baru, Purbaya Yudhi Sadewa. Studi ini menggabungkan teknik Deep Learning, Clustering, dan Time-Series Forecasting untuk menghasilkan wawasan kebijakan yang komprehensif.

## 🌟 Fitur Utama & Metodologi
Sentiment Analysis (IndoBERT): Klasifikasi sentimen (Positif, Netral, Negatif) menggunakan model Transformer yang telah dilatih khusus pada korpus bahasa Indonesia.
Public Opinion Clustering (TF-IDF + K-Means): Pengelompokan komentar ke dalam 5 topik utama (seperti kebijakan fiskal, hutang negara, dan kenaikan pajak) menggunakan pembobotan kata yang informatif.
Trend Forecasting (Prophet): Prediksi perubahan suasana hati publik dan pola keterlibatan di masa depan berdasarkan data historis harian.

## 🛠️ Tech Stack
Language: Python
Model Sentimen: IndoBERT (Hugging Face)
Clustering: Scikit-Learn (K-Means), TF-IDF Vectorizer
Forecasting: Facebook Prophet
Data Scraping: YouTube Data API v3

## 📈 Ringkasan Hasil (Insight)
Akurasi Model: Fine-tuning IndoBERT dengan 1.000 data seimbang menghasilkan akurasi validasi sebesar 93,93%.
Sentimen Dominan: Opini publik cenderung didominasi oleh ekspresi netral dan positif moderat terkait penunjukan menteri baru.
Prediksi Tren: Analisis Prophet menunjukkan sentimen publik relatif stabil dengan fluktuasi mingguan yang mengikuti pola aktivitas diskusi di hari kerja.

## 📂 Struktur Repositori
FinalReport.pdf: Laporan teknis lengkap proyek.
text_processing_sentiment.ipynb: Notebook eksperimen lengkap (Scraping hingga Forecasting).
data/: Master dataset komentar YouTube hasil pembersihan.

## 👥 Tim Pengembang (Sains Data UNESA)
1. Abdullah Al-Firdaus Nuzula (24031554008)
2. Halilatunnisa (24031554130)
3. Elvira Tiara Suci Tambunan (24031554213)

Dosen Pengampu: Ulfa Siti Nuraini, S.Stat., M.Stat.
