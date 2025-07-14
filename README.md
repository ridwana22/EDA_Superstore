# Analisis Data Eksploratif (EDA) - Dataset Superstore
Proyek ini merupakan analisis data eksploratif (EDA) dari dataset "Superstore". Tujuannya adalah untuk menggali wawasan bisnis yang tersembunyi, memahami tren penjualan dan profitabilitas, serta mengidentifikasi area mana yang berkinerja baik dan mana yang memerlukan perhatian lebih lanjut.

## 📊 Analisis yang Dilakukan
Notebook ini mencakup beberapa tahap analisis utama:
1.  **Pembersihan Data**
    * Memuat dataset `superstore.csv`.
    * Memeriksa dan menangani nilai yang hilang (*missing values*) dan data duplikat untuk memastikan kualitas data.

2.  **Analisis Profitabilitas**
    * **Hubungan Sales vs Profit**: Menganalisis korelasi antara total penjualan dengan keuntungan yang dihasilkan.
    * **Kinerja Produk**: Mengidentifikasi `Sub-Category` produk yang paling menguntungkan dan yang paling merugikan.
    * **Margin Keuntungan**: Membuat metrik baru yaitu `Profit Margin` (`Profit/Sales`) untuk mengukur efisiensi penjualan dari setiap `Sub-Category`.

3.  **Analisis Geografis**
    * Menganalisis performa penjualan dan keuntungan berdasarkan `State` (Negara Bagian).
    * Mengidentifikasi 10 negara bagian dengan penjualan dan keuntungan tertinggi.

4.  **Analisis Deret Waktu (*Time Series*)**
    * Memvisualisasikan tren penjualan (`Sales`) dari waktu ke waktu berdasarkan `Order Date`.
    * Menganalisis tren tahunan untuk `Sales` dan `Profit` untuk melihat pertumbuhan bisnis secara keseluruhan.

## 💡 Temuan Utama
Dari analisis yang telah dilakukan, beberapa wawasan penting berhasil diidentifikasi:
* **Produk Tidak Menguntungkan**: Sub-kategori produk seperti **Tables** dan **Bookcases** secara konsisten menghasilkan kerugian meskipun penjualannya cukup tinggi.
* **Penjualan Tinggi, Profit Rendah**: Produk **Binders** dan **Paper** merupakan produk yang paling banyak terjual, namun Binders memiliki rata-rata keuntungan yang sangat rendah.
* **Performa Regional**: **California** dan **New York** adalah pasar kunci dengan total penjualan dan keuntungan tertinggi. Di sisi lain, wilayah **Central** tercatat memiliki profitabilitas terendah.
* **Tren Pertumbuhan**: Secara keseluruhan, bisnis menunjukkan **tren pertumbuhan positif** dari tahun ke tahun, baik dari sisi penjualan maupun keuntungan.

## 🚀 Cara Menjalankan

1.  Pastikan Anda telah menginstal semua *library* Python yang dibutuhkan.
2.  Siapkan file dataset `superstore.csv` di direktori yang sama.
3.  Jalankan sel-sel kode di dalam *notebook* `Superstore.ipynb` secara berurutan untuk mereproduksi analisis dan visualisasi.
