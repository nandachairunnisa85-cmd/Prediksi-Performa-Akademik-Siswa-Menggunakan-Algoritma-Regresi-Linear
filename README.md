# Prediksi Performa Akademik Siswa Menggunakan Regresi Linear

NANDA CHAIRUNNISA 
TI B

## 📌 Deskripsi Proyek
Proyek ini adalah implementasi Machine Learning menggunakan algoritma **Linear Regression** (Regresi Linear) untuk memprediksi Indeks Performa (Performance Index) siswa. 

## 📊 Dataset
Dataset yang digunakan berasal dari https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression , fiturnya sebagai berikut:
- **Hours Studied**: Jumlah jam belajar.
- **Previous Scores**: Nilai ujian sebelumnya.
- **Extracurricular Activities**: Keterlibatan dalam ekstrakurikuler (Telah di-*encode* menjadi `1` untuk Yes dan `0` untuk No).
- **Sleep Hours**: Jumlah jam tidur.
- **Sample Question Papers Practiced**: Jumlah latihan soal yang dikerjakan.
- **Performance Index**: Nilai akhir/performa siswa (Variabel Target).

## 🛠️ Teknologi yang Digunakan
**Manipulasi & Analisis Data:**
  * `pandas`: Untuk memuat dataset dan manipulasi struktur data (Dataframe).
  * `numpy`: Untuk komputasi array dan operasi matematika tingkat lanjut.
* **Visualisasi Data:**
  * `matplotlib.pyplot` & `seaborn`: Untuk membuat grafik eksplorasi data (EDA) agar pola dan distribusi data lebih mudah dipahami.
* **Machine Learning (`scikit-learn`):**
  * `train_test_split`: Untuk membagi dataset menjadi data latih (training) dan data uji (testing).
  * `StandardScaler`: Untuk melakukan standarisasi skala data agar performa model lebih optimal dan stabil.
  * `LinearRegression`: Algoritma utama yang digunakan untuk memprediksi nilai.
  * `mean_squared_error` & `r2_score`: Metrik evaluasi untuk mengukur tingkat akurasi dan persentase error dari prediksi model.

