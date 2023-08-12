# Datathon Open Competition - Peramalan Kecepatan Rata-rata Jalan London

## Ikhtisar

Repository ini berisi hasil kerja saya untuk Kompetisi Datathon Open yang diselenggarakan oleh RISTEK Universitas Indonesia. Kompetisi ini bertujuan untuk meramalkan kecepatan rata-rata jalan di London dari tanggal 23 hingga 29 Februari menggunakan data historis dari 1 hingga 22 Februari.

## Dataset

Dataset kompetisi dapat diakses di [Kaggle](https://www.kaggle.com/link-dataset-di-sini). Ini berisi informasi historis tentang kecepatan rata-rata jalan di London untuk periode waktu yang telah ditentukan.

## Notebook

Berikut ini adalah beberapa notebook yang memperlihatkan langkah-langkah kerja dan pendekatan saya dalam kompetisi ini:

1. [Notebook dengan MLforecast, LGBM, dan XGBoostRegressor](https://github.com/nama-username/nama-repo-anda/blob/main/notebooks/notebook_datathon.ipynb) - Notebook ini menjelaskan langkah-langkah yang saya ambil untuk melakukan pra-pemrosesan data, melakukan rekayasa fitur, dan melatih model menggunakan library MLforecast, model LGBM, dan model XGBoostRegressor. Saya juga menggunakan library Optuna untuk penyetelan parameter.

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
