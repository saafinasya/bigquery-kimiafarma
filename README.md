# 📊 Kimia Farma Performance Analytics (2020-2023)

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis kinerja bisnis Kimia Farma dari tahun 2020 hingga 2023. Analisis mencakup transaksi penjualan, inventaris, performa cabang, korelasi rating, hingga total profit. Data diolah dan divisualisasikan menggunakan *Google Looker Studio*.

## 📂 Dataset & Queries

### 🔹 *Tabel Utama*
- kf_final_transaction - Data transaksi final dari seluruh cabang.
- kf_inventory - Data inventaris produk di cabang.
- kf_kantor_cabang - Informasi kantor cabang Kimia Farma.
- kf_product - Informasi detail produk yang dijual.

### 🔹 *Tabel Hasil Analisis*
- analisa_kinerja_cabang - Analisis performa tiap cabang.
- analisa_korelasi_rating - Korelasi antara rating dan faktor lainnya.
- analisa_pendapatan_cabang - Total pendapatan per cabang.
- analisa_top5_cabang - 5 cabang dengan performa terbaik.
- analisa_top_10_nett_profit - 10 cabang dengan laba bersih tertinggi.
- analisa_top_10_total_profit - 10 cabang dengan total profit tertinggi.
- analisa_total_profit_per_cabang - Total profit yang dihasilkan tiap cabang.
- analisa_transaksi_per_cabang - Jumlah transaksi per cabang.

### 🔹 *Queries yang Digunakan*
- query_analisa_pendapatan_cabang.sql : https://console.cloud.google.com/bigquery?sq=849740054243:2be65395d33d4d42ac3a5ba498c88f81
- query_analisa_total_profit.sql : https://console.cloud.google.com/bigquery?sq=849740054243:1c618ce8d25548b4a69838d61b1362e7
- query_analisa_kinerja_cabang.sql : https://console.cloud.google.com/bigquery?sq=849740054243:f887821931e84f7a85537dab4c462c39
- query_analisa_korelasi_rating.sql : https://console.cloud.google.com/bigquery?sq=849740054243:4047ce7451684786a276aa61c985d32f
- query_analisis_top10_nett_profit.sql: https://console.cloud.google.com/bigquery?sq=849740054243:270bbaa6ba1a429fbcd87120a92b667c
- query_analisis_top10_total_profit.sql : https://console.cloud.google.com/bigquery?sq=849740054243:8fc00e1e124848c89ef3d8487e83ee7c
- analisis_top5_cabang_rating.sql : https://console.cloud.google.com/bigquery?sq=849740054243:35d7e03135aa4c7d8b7af9a40acaa783

## 🛠 Tools & Technologies
- *Google BigQuery* - Untuk mengolah dan menyimpan data.
- *Google Looker Studio* - Untuk visualisasi dan pembuatan dashboard.

## 📊 Dashboard
Dashboard utama dibuat menggunakan *Google Looker Studio*, menampilkan insights seperti:
- Tren transaksi tahunan.
- Total profit masing-masing provinsi.
- Analisis profit dan revenue.
- Korelasi antara rating pelanggan dan performa bisnis.
