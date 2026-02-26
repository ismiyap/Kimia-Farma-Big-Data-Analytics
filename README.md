# Big Data Analytics Intern - Kimia Farma

Project ini merupakan bagian dari **Project-Based Internship** (VIX) yang diselenggarakan oleh Rakamin Academy bekerja sama dengan Kimia Farma. Fokus utama project ini adalah melakukan analisis kinerja bisnis Kimia Farma pada periode tahun 2020 hingga 2023.

## **Objektif**
Tujuan utama dari tantangan ini adalah mengevaluasi kinerja bisnis dengan mengolah dataset transaksi, kantor cabang, dan produk untuk menghasilkan tabel analisa yang komprehensif.

## **Data yang Digunakan**
Proses analisis ini melibatkan empat dataset utama yang diimpor ke BigQuery:
* **kf_final_transaction**: Data detail transaksi pelanggan.
* **kf_inventory**: Data stok produk di berbagai cabang.
* **kf_kantor_cabang**: Informasi lokasi dan rating kantor cabang.
* **kf_product**: Data detail produk obat beserta harganya.

## **Langkah Pengerjaan**
1. **Importing Dataset**: Mengunggah dataset ke Google BigQuery dengan skema yang sesuai.
2. **Data Transformation**: Membuat tabel analisa gabungan menggunakan SQL JOIN.
3. **Logic Perhitungan Laba**: Mengimplementasikan logika persentase laba berdasarkan kategori harga obat:
    - Harga <= Rp 50.000 (Laba 10%).
    - Harga > Rp 50.000 - 100.000 (Laba 15%).
    - Harga > Rp 100.000 - 300.000 (Laba 20%).
    - Harga > Rp 300.000 - 500.000 (Laba 25%).
    - Harga > Rp 500.000 (Laba 30%).
4. **Data Visualization**: Menghubungkan tabel analisa ke Google Looker Studio untuk pembuatan dashboard interaktif.

## **Tools**
* **Google BigQuery**: Digunakan sebagai data warehouse dan pengolahan query SQL.
* **Google Looker Studio**: Digunakan untuk pembuatan visualisasi data (Dashboard Performance Analytics).
* **GitHub**: Digunakan sebagai tempat dokumentasi dan penyimpanan syntax SQL.

