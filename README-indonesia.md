# Datathon Open Competition - Forecasting Kecepatan Rata-rata Jalan London

## Ikhtisar

Repository ini berisi hasil kerja saya untuk Kompetisi Datathon Open yang diselenggarakan oleh RISTEK Universitas Indonesia. Kompetisi ini bertujuan untuk meramalkan kecepatan rata-rata jalan di London dari tanggal 23 hingga 29 Februari menggunakan data historis dari 1 hingga 22 Februari.

## Dataset

Dataset kompetisi dapat diakses di [Kaggle](https://www.kaggle.com/link-dataset-di-sini). Ini berisi informasi historis tentang kecepatan rata-rata jalan di London untuk periode waktu yang telah ditentukan. Data Tambahan yang digunakan di Notebook tersedia [Disini](https://github.com/alifrachmat2002/datathon-ristek/blob/ffb8d3c09ff86cb6ae63fec1bbb59745c50f2864/informasi-jalan.csv)

## Notebook

Berikut ini adalah beberapa notebook yang memperlihatkan langkah-langkah kerja dan pendekatan saya dalam kompetisi ini:

1. [Notebook for preprocessing the data](https://github.com/alifrachmat2002/datathon-ristek/blob/ead0edccdc00f1a8f88814767787ccfadd1d2aab/Datathon%20-%20Preprocessing%20Code.ipynb) - Notebook ini menjelaskan langkah-langkah yang saya ambil untuk melakukan preprocessing dan membersihkan data.
2. [Notebook with MLforecast and LGBM Model](https://github.com/alifrachmat2002/datathon-ristek/blob/754418e8905aef373d6120f685f3f2c05bba2010/Datathon%20-%20LightGBM.ipynb), and [Notebook with MLforecast and XGBoostRegressor Model](https://github.com/alifrachmat2002/datathon-ristek/blob/ef639969163d0b39e31ede990b332de08745b1f2/Datathon%20-%20XGBRegressor.ipynb) -  Notebook ini menjelaskan langkah-langkah yang saya ambil untuk melatih model menggunakan library MLforecast, model LGBM, dan model XGBoostRegressor. Saya juga menggunakan library Optuna untuk melakukan tuning hyperparameter.

## Model yang Digunakan

### MLforecast

MLforecast adalah library yang dirancang khusus untuk meramalkan time series. Ini menyediakan berbagai alat untuk mengelola data time series dan mengimplementasikan model peramalan.

### LightGBM (LGBM)

LightGBM adalah kerangka kerja gradient boosting yang menggunakan algoritma pembelajaran berbasis pohon. Terkenal karena efisiensinya dan akurasinya dalam menangani dataset besar.

### XGBoostRegressor

XGBoost adalah algoritma gradient boosting lain yang populer karena performa tinggi dan fleksibilitasnya dalam berbagai tugas pembelajaran mesin, termasuk regresi.

## Hasil

Setelah melakukan pra-pemrosesan data yang cermat, rekayasa fitur, dan penyetelan model, saya berhasil mencapai nilai SMAPE terendah sebesar 8,52 pada set pelatihan dan 8,57 pada set pengujian.

Meskipun saya tidak lolos ke babak final, kompetisi ini adalah pengalaman belajar yang berharga, yang memungkinkan saya menerapkan teknik peramalan canggih dan meningkatkan keterampilan dalam analisis data dan pembelajaran mesin.
