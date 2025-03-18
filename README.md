# Portofolio Analisis Data

# 1. Case Study Data Mining Course

Proyek ini merupakan portofolio analisis data yang mencakup berbagai teknik eksplorasi dan pemodelan data, mulai dari eksplorasi awal, hingga analisis opini publik dari media sosial. 
Proyek ini terbagi menjadi 4 Case Study dan 1 Final Project yang dikerjakan selama menjalani perkuliahan pada kelas Data Mining.

## 🧠 Ruang Lingkup Analisis

### 1. 📊 **Exploratory Data Analysis (EDA)**
- Menganalisis distribusi data.
- Menampilkan visualisasi tren data.

### 2. 🔗 **Association Rule Mining**
- Menggunakan algoritma Apriori untuk menemukan pola pembelian yang sering terjadi (frequent itemsets).
- Menemukan hubungan antar produk untuk rekomendasi produk.

### 3. 🧩 **Clustering Analysis**
- Menggunakan K-Means untuk segmentasi pelanggan berdasarkan perilaku pembelian.
- Visualisasi hasil clustering dalam bentuk scatter plot dan PCA.

### 4. 📈 **Korelasi dan Regresi**
- Menggunakan analisis korelasi Pearson untuk memahami hubungan antar variabel numerik.
- Membangun model regresi linear untuk memprediksi pendapatan berdasarkan fitur tertentu.

### 5. 🌐 **Social Network Analysis (SNA)**
- Membangun dan menganalisis jaringan hubungan antar pengguna media sosial.
- Menghitung centrality (degree, betweenness) dan menemukan komunitas dengan modularity.

---

## 🧰 Tools & Teknologi

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib & Seaborn (visualisasi)
- Mlxtend (Apriori)
- Scikit-learn & Yellowbrick (Clustering & Regression)
- Gephi (Social Network Analysis)
- NetworkX (Social Network Analysis)
- Google Colab

---

## 📝 Catatan

- Data yang digunakan telah dianonimkan dan sebagian merupakan data sintetis untuk keperluan edukasi.
- Analisis ini ditujukan untuk memenuhi tugas perkuliahan.

---

# 2. Skripsi 

# 🌾 Peramalan Harga Beras Nasional Menggunakan Long Short-Term Memory

Proyek ini merupakan bagian dari tugas akhir/skripsi saya yang berjudul **"Peramalan Harga Beras Nasional Menggunakan Long Short-Term Memory"**. Tujuan dari penelitian ini adalah untuk membangun model time series forecasting berbasis deep learning untuk memprediksi harga beras 3 bulan ke depan secara lebih akurat.

---

## 🎯 Latar Belakang

Harga beras merupakan indikator penting dalam kestabilan ekonomi nasional. Prediksi harga yang akurat dapat membantu pengambilan keputusan dalam rantai pasok pangan, kebijakan pemerintah, serta membantu masyarakat dalam merencanakan konsumsi.

---

## 🧠 Metodologi

1. **Pengumpulan Data**
   - Sumber data: [Badan Pangan Nasional](https://panelharga.badanpangan.go.id/)
   - Data: Harga beras nasional per bulan (dalam rupiah), kurun waktu [2018 - 2023]

2. **Pra-pemrosesan Data**
   - Mengatasi missing values
   - Normalisasi data menggunakan MinMaxScaler

3. **Splitting Data**
   Data dibagi menjadi data training dan data testing dengan proporsi berdasarkan time series sebagai berikut:
	 - 70% data training dan 30% data testing
   - 80% data training dan 20% data testing
   - 90% data training dan 10% data testing
 
4. **Modeling**
   - Arsitektur model: LSTM 
   - Framework: TensorFlow/Keras
   - Optimizer: Adam, Loss function: MSE

5. **Evaluasi**
   - Metrik evaluasi: RMSE, MAE

---

## 📈 Hasil dan Temuan

- Visualisasi hasil prediksi menunjukkan tren yang mendekati harga aktual.
- RMSE model akhir: `43,78`, MAE: `36,6`

---
## 🧰 Tools & Library

- Python 3
- Pandas & NumPy
- TensorFlow / Keras
- Matplotlib / Seaborn
- Scikit-learn

---

## 📊 Contoh Output

- Grafik perbandingan harga aktual vs harga prediksi
- Grafik loss selama training
- Tabel evaluasi model


---

## 📬 Kontak

- 📧 Email: vaniaputrimusdani@email.com  
- 🔗 LinkedIn: [linkedin.com/in/vania-putri-musdani-19603211b](https://linkedin.com/in/vania-putri-musdani-19603211b)  
- 🐙 GitHub: [@vaniamusdani](https://github.com/vaniamusdani)
