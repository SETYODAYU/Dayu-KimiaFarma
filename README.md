<img width="252" height="25" alt="image" src="https://github.com/user-attachments/assets/f51de910-51d7-4767-9042-4389362a8eae" />Kimia Farma Performance Analytics Dashboard (2020-2023)
Project Overview

Proyek ini adalah bagian dari Final Task Big Data Analytics untuk menganalisis kinerja bisnis PT Kimia Farma Tbk. Tujuan utamanya adalah untuk mentransformasi data mentah dari BigQuery menjadi dashboard interaktif di Google Looker Studio guna membantu manajemen dalam memantau pendapatan, profitabilitas, dan kualitas layanan di seluruh cabang di Indonesia.
Tech Stack

    Database & Processing: Google BigQuery (SQL)

    Visualization: Google Looker Studio

    Data Source: Kimia Farma Internal Dataset (2020-2023)

Repository Structure

    /datasets: Berisi 4 file CSV mentah (Transaction, Inventory, Branch, Product).

    /scripts: Berisi file SQL (analisa_performance_table.sql) untuk transformasi data.

    /output: Berisi screenshot dashboard dan file presentasi.

Data Transformation (SQL Logic)

Dalam proses pengolahan data, saya membuat tabel analisa_performance yang menggabungkan seluruh data mentah. Beberapa metrik yang dihitung secara otomatis meliputi:

    Nett Sales: Harga produk dikurangi persentase diskon.

    Persentase Laba: Ditentukan berdasarkan kategori harga produk (10% - 30%).

    Nett Profit: Keuntungan bersih yang diterima perusahaan setelah dikurangi biaya operasional/laba cabang.

Key Insights from Dashboard

    Revenue Stability: Perusahaan menjaga stabilitas pendapatan bulanan di kisaran Rp6,11 M - Rp7,64 M.

    Top Performance: Jawa Barat merupakan provinsi dengan kontribusi transaksi dan profit tertinggi.

    Service Evaluation: Ditemukan kesenjangan (gap) pada beberapa cabang yang memiliki rating fisik toko tinggi namun rating kepuasan transaksi rendah (skala 4.0).

How to Access

    Interactive Dashboard: https://lookerstudio.google.com/s/haf_zFCKLOA

    Presentation Video: https://drive.google.com/drive/folders/1abboUP5U1xJfjJlB-wfXQ9VJ4YQygPpO?usp=drive_link
