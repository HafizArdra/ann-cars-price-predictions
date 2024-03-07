# Report ANN Cars Price Prediction 

<h2>Dataset : https://www.kaggle.com/datasets/yashpaloswal/ann-car-sales-price-prediction</h2>



<h2>Overview</h2>
Proyek ini bertujuan untuk memprediksi harga mobil menggunakan jaringan saraf tiruan (ANN) dan regresi linear. Dataset yang digunakan berisi informasi tentang gaji tahunan pelanggan, hutang kartu kredit, jumlah pembelian mobil, dan fitur lain yang relevan. Tujuannya adalah untuk membangun dan membandingkan kinerja dua model: model regresi linear dan model ANN.

<h2>Dataset</h2>
Dataset yang digunakan untuk proyek ini berisi informasi tentang pembeli mobil, termasuk gaji tahunan, hutang kartu kredit, dan jumlah yang dihabiskan untuk membeli mobil. Setelah memuat dataset, kolom-kolom yang tidak perlu seperti nama pelanggan, email, negara, dan jenis kelamin dihapus untuk mempersiapkan data untuk analisis.

<h2>Preprocessing</h2>
Data menjalani tahap preprocessing, termasuk penskalaan fitur numerik menggunakan MinMaxScaler dan pembagian dataset menjadi set pelatihan dan pengujian. Pra-pemrosesan memastikan bahwa data siap untuk dimasukkan ke dalam model pembelajaran mesin.

<h2>Linear Regression</h2>
Model regresi linear dilatih pada data pelatihan dan dievaluasi menggunakan skor R-squared. Model tersebut menunjukkan kinerja yang cukup baik namun terbatas dalam menangkap pola kompleks dalam data.

<h2>Artificial Neural Network (ANN)</h2>
Sebuah model ANN dengan satu lapisan tersembunyi dibangun menggunakan API Sekuensial Keras. Model tersebut dilatih pada data pelatihan dengan 50 epoch, dan kinerjanya dievaluasi menggunakan metrik kehilangan dan akurasi pelatihan dan validasi. Model ANN menunjukkan kinerja yang ditingkatkan dibandingkan dengan regresi linear, menangkap hubungan yang lebih kompleks dalam data.

<h2>Evaluation</h2>
Kinerja kedua model dievaluasi menggunakan skor R-squared pada data pengujian. Selain itu, kesalahan rata-rata absolut (MAE) dan kesalahan kuadrat rata-rata (MSE) dihitung untuk mengukur akurasi prediksi model. Model ANN melampaui model regresi linear, mencapai skor R-squared yang lebih tinggi dan metrik kesalahan yang lebih rendah.

<h2>Conclusion</h2>
Secara keseluruhan, model ANN terbukti lebih efektif dalam memprediksi harga mobil dibandingkan dengan regresi linear. Dengan memanfaatkan jaringan saraf, model ANN mampu menangkap hubungan non-linear dalam data, menghasilkan kinerja prediktif yang lebih baik. Proyek ini menunjukkan kegunaan jaringan saraf tiruan dalam tugas regresi dan menyoroti pentingnya memilih model pembelajaran mesin yang sesuai untuk dataset dan tugas yang berbeda.

<h3><i>Note:</i></h3>
Confusion matrix dan classification report tidak digunakan dalam proyek ini karena lebih cocok untuk masalah klasifikasi, sedangkan proyek ini berfokus pada regresi. Sebagai gantinya, metrik evaluasi regresi seperti skor R-squared, MAE, dan MSE digunakan.
