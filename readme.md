# Dokumentasi Project Klasifikasi Iris
## Hari 1: Persiapan dan Preprocessing Data

### Deskripsi Project
Project ini bertujuan untuk mengklasifikasikan bunga Iris berdasarkan empat fitur utama: panjang sepal, lebar sepal, panjang petal, dan lebar petal. Dataset ini terdiri dari 150 sampel dengan tiga kelas berbeda.

### Struktur Project
```
project1_iris/
├── Day1_Iris_Classification.ipynb
├── X_train_scaled.npy
├── X_test_scaled.npy
├── y_train.npy
├── y_test.npy
├── pairplot.png
└── correlation_matrix.png
```

### Tahapan Preprocessing
1. **Persiapan Data**
   - Dataset dimuat menggunakan sklearn.datasets
   - Data dikonversi ke DataFrame untuk memudahkan analisis
   - Tidak ditemukan missing values dalam dataset

2. **Eksplorasi Data**
   - Total 150 sampel dengan 4 fitur
   - Setiap kelas memiliki 50 sampel (dataset seimbang)
   - Visualisasi menggunakan pairplot dan correlation matrix

3. **Preprocessing**
   - Data dibagi menjadi 80% training dan 20% testing
   - Fitur distandarisasi menggunakan StandardScaler
   - Data hasil preprocessing disimpan dalam format .npy

### Hasil Analisis
- Dataset sangat bersih tanpa missing values
- Terdapat korelasi kuat antara petal length dan petal width
- Data telah siap untuk proses pemodelan di hari kedua

### Cara Menjalankan
1. Pastikan semua library terinstal:
   ```python
   pip install pandas numpy scikit-learn seaborn matplotlib
   ```
2. Buka Jupyter Notebook
3. Jalankan setiap cell secara berurutan

### Catatan Penting
- Gunakan Python 3.x
- Pastikan semua visualisasi tersimpan sebelum menutup notebook
- Hasil preprocessing disimpan otomatis untuk digunakan di hari kedua