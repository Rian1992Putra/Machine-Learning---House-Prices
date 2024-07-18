# Machine-Learning---House-Prices

# Business Problem Understanding
## Context
Harga rumah mengalami kenaikan setiap tahunnya. Hal itu dikarenakan meningkatnya kebutuhan akan rumah namun disaat yang bersamaan berkurangnya lahan yang tersedia. Harga rumah dapat berbeda-beda disetiap wilayah tergantung dari kondisi rumah, kondisi wilayah sekitar serta penilaian pribadi dari penjual rumah.

## Problem Statement
Berdasarkan konteks diatas dapat dilihat bahwa pentingnya mencari harga rumah yang sesuai dengan keinginan namun tetap mendapatkan value setinggi mungkin.

## Goals
Berikut merupakan beberapa tujuan yang ingin dicapai dalam pembuatan machine learning ini:

Prediksi Harga: Tujuan utama adalah mengembangkan model machine learning yang dapat memprediksi dengan akurat harga jual rumah. Ini akan membantu pembeli dan penjual memahami nilai pasar dari sebuah properti.

Wawasan Umum: Memperoleh wawasan terkait faktor-faktor yang memengaruhi harga rumah. Ini dapat membantu dalam pengambilan keputusan berdasarkan data yang telah ada.

Analytics Approach
Analisis diawali dengan melakukan pengecekan statistik serta eksplorasi data untuk mengetahui faktor-faktor yang berpengaruh terhadap harga rumah, selanjutnya melakukan data cleaning dan preprocessing data untuk tahap persiapan melakukan modelling. Kemudian dilakukan training data pada beberapa benchmark modelling untuk dapat membandingkan tingkat eror dari masing - masing model sehingga dapat memilih model dengan tingkat error terendah (model terbaik).

Metric Evaluation
Metrik evaluasi yang digunakan untuk mengitung performance dari machine learning yang digunakan dapat berbagai macam diantaranya adalah RMSE, MAE, dan MAPE. Metrik yang digunakan akan disesuaikan dengan kebutuhan dan kondisi data. Adapun pengertian dari tiap-tiap metrik yaitu : 

- Root Mean Square Error (RMSE) adalah salah satu metrik evaluasi yang umum digunakan dalam machine learning, khususnya dalam konteks regresi. Metrik ini digunakan untuk mengukur sejauh mana model regresi cocok dengan data aktual atau sejauh mana perbedaan antara nilai yang diprediksi oleh model dengan nilai sebenarnya. RMSE mengukur kesalahan model regresi dengan menghitung akar kuadrat rata-rata dari perbedaan antara nilai yang diprediksi oleh model dengan nilai sebenarnya (ground truth). RMSE memberikan bobot lebih besar pada kesalahan besar, yang berarti kesalahan besar akan lebih berdampak pada nilai RMSE daripada kesalahan kecil. RMSE memiliki satuan yang sama dengan target variabel, yang membuatnya mudah diinterpretasikan. Sebagai contoh, jika Anda memodelkan harga rumah, RMSE akan memiliki satuan mata uang yang sama dengan harga rumah, seperti dolar atau rupiah.

- Mean Absolute Error (MAE) adalah salah satu metrik evaluasi yang digunakan dalam statistik dan machine learning untuk mengukur sejauh mana model prediksi berbeda dari nilai sebenarnya. MAE mengukur kesalahan prediksi dengan mengambil rata-rata dari selisih absolut antara prediksi model dan nilai sebenarnya. Semakin rendah nilai MAE, semakin baik kinerja model dalam melakukan prediksi. MAE mengukur kesalahan model dengan menghitung rata-rata dari selisih absolut antara nilai yang diprediksi oleh model dan nilai sebenarnya. MAE memberikan bobot yang sama pada semua kesalahan, tanpa memperhatikan apakah kesalahan tersebut besar atau kecil.

- MAPE (Mean Absolute Percentage Error) adalah metrik evaluasi yang digunakan untuk mengukur sejauh mana model prediksi berbeda dari nilai sebenarnya dalam bentuk persentase. MAPE sangat berguna dalam kasus ingin mengukur akurasi prediksi dalam konteks persentase kesalahan relatif terhadap nilai sebenarnya. Metrik ini umumnya digunakan dalam peramalan dan perencanaan untuk mengukur kualitas model prediksi dalam hal persentase kesalahan. MAPE adalah metrik yang mengukur kesalahan model dalam bentuk persentase dari kesalahan relatif terhadap nilai sebenarnya. MAPE berguna ketika Anda ingin memahami sejauh mana model regresi menghasilkan kesalahan dalam bentuk persentase dari nilai sebenarnya.
