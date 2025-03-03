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
- query_analisa_pendapatan_cabang.sql
- query_analisa_total_profit.sql
- query_analisa_kinerja_cabang.sql
- query_analisa_korelasi_rating.sql
- query_analisis_top10_nett_profit.sql
- query_analisis_top10_total_profit.sql
- analisis_top5_cabang_rating.sql

## 🛠 Tools & Technologies
- *Google BigQuery* - Untuk mengolah dan menyimpan data.
- *Google Looker Studio* - Untuk visualisasi dan pembuatan dashboard.

## 📊 Dashboard
Dashboard utama dibuat menggunakan *Google Looker Studio*, menampilkan insights seperti:
- Tren transaksi tahunan.
- Total profit masing-masing provinsi.
- Analisis profit dan revenue.
- Korelasi antara rating pelanggan dan performa bisnis.
