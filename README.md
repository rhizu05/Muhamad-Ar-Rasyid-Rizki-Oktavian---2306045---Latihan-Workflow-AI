# Analisis Penjualan dan Prediksi Restock dengan Decision Tree

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data penjualan produk, membersihkan data, dan melatih model menggunakan **Decision Tree Classifier** untuk memprediksi apakah suatu produk perlu di-restock atau tidak berdasarkan jumlah terjual dan stok yang tersedia. Selain itu, proyek ini juga mencakup visualisasi hubungan antara jumlah terjual, stok, dan keuntungan menggunakan **matplotlib**.

## Cara Menjalankan Kode

### 1. Persiapan Lingkungan
Pastikan Python sudah terinstal di sistem Anda. Kemudian, instal pustaka yang dibutuhkan dengan perintah berikut:
```
pip install pandas scikit-learn matplotlib
```

### 2. Menjalankan Analisis Data dan Pelatihan Model
1. Simpan dataset penjualan dalam format CSV dengan nama `data_penjualan_latihan.csv`.
2. Jalankan skrip untuk membaca dataset, membersihkan data, dan menambahkan fitur tambahan:
   ```bash
   python data_processing.py
   ```
3. Jalankan skrip untuk melatih model menggunakan **Decision Tree Classifier**:
   ```bash
   python train_model.py
   ```

### 3. Memprediksi Restock Produk
Untuk memprediksi apakah suatu produk perlu di-restock berdasarkan jumlah terjual dan stok saat ini, jalankan perintah berikut:
```
python predict_restock.py
```
Jika stok kurang dari 5 unit, hasil prediksi akan seperti berikut:
```
Prediksi untuk produk baru (Jumlah Terjual = 8, Stok = 3):
  Produk perlu di-restock!
```

### 4. Visualisasi Data
Untuk melihat hubungan antara **Jumlah Terjual, Stok, dan Keuntungan**, jalankan perintah berikut:
```
python visualize_data.py
```
Grafik akan menampilkan titik-titik yang menunjukkan data penjualan dengan warna yang merepresentasikan jumlah stok.

---
Proyek ini dirancang untuk membantu menganalisis data penjualan dan memberikan rekomendasi restock berdasarkan data yang tersedia.

