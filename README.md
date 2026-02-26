# Big Data Analytics Intern - Kimia Farma

[cite_start]Project ini merupakan bagian dari **Project-Based Internship** (VIX) yang diselenggarakan oleh Rakamin Academy bekerja sama dengan Kimia Farma[cite: 1, 2, 3]. [cite_start]Fokus utama project ini adalah melakukan analisis kinerja bisnis Kimia Farma pada periode tahun 2020 hingga 2023[cite: 5].

## **Objektif**
[cite_start]Tujuan utama dari tantangan ini adalah mengevaluasi kinerja bisnis dengan mengolah dataset transaksi, kantor cabang, dan produk untuk menghasilkan tabel analisa yang komprehensif[cite: 16, 17].

## **Data yang Digunakan**
[cite_start]Proses analisis ini melibatkan empat dataset utama yang diimpor ke BigQuery[cite: 19, 20]:
* [cite_start]**kf_final_transaction**: Data detail transaksi pelanggan[cite: 21, 126].
* [cite_start]**kf_inventory**: Data stok produk di berbagai cabang[cite: 22, 147].
* [cite_start]**kf_kantor_cabang**: Informasi lokasi dan rating kantor cabang[cite: 23, 155].
* [cite_start]**kf_product**: Data detail produk obat beserta harganya[cite: 24, 138].

## **Langkah Pengerjaan**
1. [cite_start]**Importing Dataset**: Mengunggah dataset ke Google BigQuery dengan skema yang sesuai[cite: 25].
2. [cite_start]**Data Transformation**: Membuat tabel analisa gabungan menggunakan SQL JOIN[cite: 26, 27].
3. [cite_start]**Logic Perhitungan Laba**: Mengimplementasikan logika persentase laba berdasarkan kategori harga obat[cite: 47, 48]:
    - [cite_start]Harga <= Rp 50.000 (Laba 10%)[cite: 49].
    - [cite_start]Harga > Rp 50.000 - 100.000 (Laba 15%)[cite: 50].
    - [cite_start]Harga > Rp 100.000 - 300.000 (Laba 20%)[cite: 51].
    - [cite_start]Harga > Rp 300.000 - 500.000 (Laba 25%)[cite: 52].
    - [cite_start]Harga > Rp 500.000 (Laba 30%)[cite: 52].
4. [cite_start]**Data Visualization**: (Tahap Selanjutnya) Menghubungkan tabel analisa ke Google Looker Studio[cite: 61, 62].

## **Tools**
* [cite_start]**Google BigQuery**: Data warehouse dan pengolahan query SQL[cite: 184].
* [cite_start]**Google Looker Studio**: Pembuatan visualisasi data (Dashboard Performance Analytics)[cite: 189].
* [cite_start]**GitHub**: Dokumentasi dan penyimpanan syntax SQL[cite: 113, 177].
