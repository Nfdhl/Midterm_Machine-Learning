## 📋 Rangkuman Tugas (Project Summary)

### 1. Task 1: Fraud Detection (Classification)
* **Tujuan**: Membangun model machine learning untuk mendeteksi transaksi penipuan (*fraud*) pada dataset transaksi keuangan.
* **Dataset**: IEEE-CIS Fraud Detection (Transaction & Identity).
* **Metode Utama**:
    * Handling Class Imbalance (Scale Pos Weight).
    * Feature Engineering & Encoding.
    * Model Comparison: XGBoost vs LightGBM.
* **Hasil**: Model **XGBoost** terpilih sebagai model terbaik dengan performa ROC-AUC yang tinggi.
* **Link**: [Task-1](../../tree/Task-1)

### 2. Task 2: Music Year Regression
* **Tujuan**: Memprediksi tahun rilis lagu berdasarkan fitur audio (Timbre average & covariance).
* **Dataset**: YearPredictionMSD (Million Song Dataset).
* **Metode Utama**:
    * Exploratory Data Analysis (EDA) untuk distribusi tahun.
    * Scaling data (StandardScaler) untuk normalisasi fitur audio.
    * Model Comparison: Linear Regression (Baseline) vs XGBoost Regressor.
* **Hasil**: **XGBoost Regressor** memberikan error (RMSE) yang jauh lebih rendah dibandingkan Linear Regression.
* **Link**: [Task-2](../../tree/Task-2)

### 3. Task 3: Customer Segmentation (Clustering)
* **Tujuan**: Mengelompokkan nasabah kartu kredit ke dalam segmen perilaku untuk strategi pemasaran.
* **Dataset**: CC GENERAL (Credit Card Dataset).
* **Metode Utama**:
    * Data Cleaning & Log Transformation untuk mengatasi *skewness*.
    * Reduksi Dimensi menggunakan **PCA**.
    * Penentuan Cluster Optimal dengan Elbow Method & Silhouette Score.
    * Profiling Nasabah.
* **Hasil**: Ditemukan 3 segmen utama nasabah:
    1.  **VIP/Whales**: Belanja tinggi & limit besar.
    2.  **Transactors**: Rajin belanja & bayar lunas.
    3.  **Revolvers**: Saldo tinggi & pembayaran minimum.
* **Link**: [Task-3](../../tree/Task-3)


## How to Navigate
Terdapat beberapa branch pada repo ini, masing-masing branch dengan nama Task-n dimana masing-masing branch berisi file yang berbeda sesuai dengan urutan task yang diberikan.

### Repository ini dibuat oleh:
Naufal Fadhil Muzakki Sutomo  
1103220124  
TK-46-04
