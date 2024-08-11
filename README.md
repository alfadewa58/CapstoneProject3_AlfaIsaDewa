# **CAPSTONE 3**

## Capstone Project modul 3 JCDSOL-14 Purwadhika - Customer Lifetime Value (asuransi mobil) dengan analysis Machine Learning
## Alfa Isa Dewa


## **Background**

Customer Lifetime Value (CLV) adalah metrik yang digunakan untuk memperkirakan total nilai pendapatan yang akan dihasilkan oleh seorang pelanggan selama masa hubungan mereka dengan sebuah perusahaan. CLV membantu perusahaan memahami nilai ekonomi jangka panjang dari pelanggan dan menginformasikan keputusan bisnis seperti alokasi anggaran pemasaran, strategi retensi pelanggan, dan penawaran khusus. Dengan menganalisis CLV, perusahaan dapat mengidentifikasi pelanggan yang paling berharga dan fokus pada strategi untuk mempertahankan mereka serta meningkatkan loyalitas, yang pada akhirnya dapat meningkatkan keuntungan dan pertumbuhan jangka panjang perusahaan.

Dataset ini berisi informasi terkait nilai seumur hidup pelanggan dalam konteks **asuransi kendaraan**. Data ini mencakup berbagai atribut seperti kelas kendaraan, jenis cakupan asuransi, tipe penawaran pembaruan, status pekerjaan, status pernikahan, dan tingkat pendidikan pelanggan. Selain itu, data ini juga mencatat jumlah polis, premi bulanan untuk asuransi kendaraan, jumlah klaim total, pendapatan, dan nilai seumur hidup pelanggan.

Mengetahui besarnya Customer Lifetime Value (CLV) dalam konteks asuransi kendaraan memiliki beberapa keuntungan yang sangat penting, terutama dalam strategi pemasaran dan pengelolaan bisnis. Berikut adalah beberapa keuntungan tersebut:
1. CLV memungkinkan segmentasi pelanggan berdasarkan potensi nilai jangka panjang mereka, sehingga perusahaan dapat memfokuskan sumber daya pemasaran dan layanan pelanggan pada segmen yang paling menguntungkan.
2. Ini membantu dalam mengurangi biaya akuisisi pelanggan dengan memastikan bahwa pengeluaran pemasaran tidak melebihi nilai seumur hidup pelanggan.
3. Ini memungkinkan perusahaan untuk menyediakan produk yang lebih relevan dan meningkatkan pengalaman pelanggan, yang pada akhirnya dapat meningkatkan CLV itu sendiri.

## Problem Statement

Salah satu tantangan utama yang dihadapi perusahaan asuransi adalah meningkatkan Customer Lifetime Value (CLV), yaitu total jumlah uang yang diharapkan akan dibelanjakan oleh pelanggan dengan bisnis Anda selama masa hubungan bisnis rata-rata. 
Salah satu masalah utama yang dihadapi perusahaan asuransi adalah rendahnya tingkat retensi pelanggan yang berdampak negatif pada Customer Lifetime Value (CLV), **yaitu total jumlah uang yang diharapkan akan dibelanjakan oleh pelanggan dengan bisnis atau produk yang ditawarkan**, selama masa hubungan bisnis rata-rata.


## Goals

Salah satu tujuan utama perusahaan asuransi adalah meningkatkan Customer Lifetime Value (CLV), yaitu total jumlah uang yang diharapkan akan dibelanjakan oleh pelanggan dengan bisnis Anda selama masa hubungan bisnis rata-rata. Agar dapat mencapai hal ini, perusahaan harus memahami kebutuhan pelanggan secara mendalam dan menawarkan solusi yang lebih personal serta relevan. Untuk mendukung upaya ini, perusahaan perlu mengembangkan model prediksi yang mampu mengidentifikasi pelanggan dengan potensi CLV tinggi dan rendah, memungkinkan penerapan strategi retensi dan pemasaran yang lebih efektif dan tepat sasaran.

## Analytic Approach

Jadi, yang perlu kita lakukan adalah menganalisis data untuk menemukan pola dari fitur-fitur yang ada, yang memengaruhi Customer Lifetime Value (CLV) pelanggan. Selanjutnya, kita akan membangun suatu model prediksi yang akan membantu perusahaan untuk menyediakan 'tool' prediksi CLV pelanggan baru, yang mana akan berguna untuk tim pemasaran dan penjualan dalam merancang strategi retensi dan penawaran yang lebih efektif.

## Metric Evaluation

Untuk mengevaluasi kinerja model regresi prediksi CLV, kita akan menggunakan beberapa metrik evaluasi. Pertama, Mean Absolute Error (MAE) yang mengukur rata-rata kesalahan absolut antara nilai prediksi dan nilai aktual, memberikan gambaran langsung tentang seberapa akurat model kita. Kedua, Root Mean Squared Error (RMSE) yang memberikan penalti lebih besar untuk kesalahan yang lebih besar, sangat berguna untuk mengidentifikasi model yang lebih sensitif terhadap kesalahan besar, dan Mean Absolute Percentage Error (MAPE) yang mengukur kesalahan prediksi dalam bentuk persentase, memberikan perspektif yang lebih relatif dan mudah dipahami mengenai seberapa jauh prediksi model dari nilai aktual. Dengan menggunakan metrik-metrik ini, kita dapat secara efektif mengevaluasi dan meningkatkan model prediksi CLV kita.
