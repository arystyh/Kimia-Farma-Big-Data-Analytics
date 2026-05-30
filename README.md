# Kimia Farma Big Data Analytics - Performance Dashboard (2020-2023)

## Project Overview
Proyek ini merupakan bagian dari **Project-Based Internship: Big Data Analytics** untuk Kimia Farma. Tujuan utama dari proyek ini adalah melakukan analisis mendalam terhadap performa bisnis Kimia Farma selama periode 2020 hingga 2023 dengan mengintegrasikan berbagai dataset mentah menjadi informasi strategis yang dapat digunakan oleh manajemen untuk pengambilan keputusan.

## Tech Stack
- **Google BigQuery**: Digunakan untuk Data Warehouse, proses Data Cleaning, dan Data Transformation menggunakan SQL.
- **Google Looker Studio**: Digunakan untuk Data Visualization dan pembuatan dashboard interaktif.
- **GitHub**: Digunakan untuk manajemen repositori kode SQL.

## Key Features & Insights
Dashboard ini menyajikan beberapa analisis utama:
1. **Business Snapshot**: Menampilkan metrik utama seperti Total Penjualan (Nett Sales), Total Profit, Jumlah Transaksi, dan Rata-rata Rating Transaksi.
2. **Geographical Analysis**: Visualisasi peta Indonesia (Geo Map) yang menunjukkan distribusi keuntungan (Nett Profit) per provinsi.
3. **Top 10 Performance**: Daftar 10 provinsi dengan jumlah transaksi dan pendapatan tertinggi.
4. **Service vs Facility Analysis**: Analisis perbandingan antara rating fasilitas cabang dengan rating layanan transaksi untuk mengidentifikasi area yang memerlukan perbaikan operasional.

## Repository Structure
- `kf_analysis_query.sql`: File yang berisi query SQL lengkap untuk menggabungkan tabel `kf_final_transaction`, `kf_inventory`, `kf_kantor_cabang`, dan `kf_product` serta perhitungan kolom baru seperti *Nett Sales* dan *Nett Profit*.

## How to Access
- **Looker Studio Dashboard**: [MASUKKAN LINK DASHBOARD ANDA DI SINI]
- **SQL Source Code**: Silakan cek file `.sql` di repositori ini.

---
*Dibuat oleh: Demas Aryasatya Herlambang*
