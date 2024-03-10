# Report ANN Cars Price Prediction 

<h2>Dataset : https://www.kaggle.com/datasets/yashpaloswal/ann-car-sales-price-prediction</h2>

<h2>Overview</h2>
Proyek ini bertujuan untuk memprediksi harga mobil menggunakan jaringan saraf tiruan (ANN) dan regresi linear. Dataset yang digunakan menyediakan informasi tentang gaji tahunan, hutang kartu kredit, jumlah pembelian mobil, dan fitur terkait lainnya. Tujuannya adalah membandingkan kinerja dua model: regresi linear dan ANN.

<h2>Dataset</h2>
Dataset berisi informasi pembelian mobil, termasuk gaji tahunan, hutang kartu kredit, dan biaya mobil. Data diolah dengan menghapus kolom-kolom yang tidak relevan dan penskalaan fitur numerik menggunakan MinMaxScaler.

<h2>Preprocessing</h2>
Data dibagi menjadi set pelatihan dan pengujian setelah penskalaan fitur. Langkah ini memastikan kesiapan data untuk dimasukkan ke dalam model pembelajaran mesin.

<h2>Linear Regression</h2>
Model regresi linear dievaluasi dengan menggunakan skor R-squared. Model tersebut menunjukkan kinerja yang baik tetapi terbatas dalam menangkap pola kompleks dalam data.

<h2>Artificial Neural Network (ANN)</h2>
Model ANN dengan satu lapisan tersembunyi dibangun menggunakan API Sekuensial Keras. Kinerja model dinilai menggunakan metrik kehilangan dan akurasi, dengan hasil yang lebih baik daripada regresi linear.

<h2>Evaluation</h2>
Kedua model dievaluasi dengan menggunakan skor R-squared pada data pengujian, serta MAE dan MSE. Model ANN unggul dalam semua metrik evaluasi, menunjukkan kemampuannya dalam menangkap hubungan non-linear dalam data.

<h2>Conclusion</h2>
Secara keseluruhan, model ANN terbukti lebih efektif dalam memprediksi harga mobil dibandingkan dengan regresi linear. Dengan memanfaatkan jaringan saraf, model ANN mampu menangkap hubungan non-linear dalam data, menghasilkan kinerja prediktif yang lebih baik. Proyek ini menunjukkan kegunaan jaringan saraf tiruan dalam tugas regresi dan menyoroti pentingnya memilih model pembelajaran mesin yang sesuai untuk dataset dan tugas yang berbeda.

