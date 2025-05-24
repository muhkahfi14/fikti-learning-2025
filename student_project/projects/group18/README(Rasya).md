# PROJECT FIKTI GROUP 18

Prediksi Nilai Ujian Mahasiswa dengan Regresi Linear

📌 Deskripsi
Project ini bertujuan untuk memprediksi nilai ujian mahasiswa (exam_score) berdasarkan berbagai kebiasaan belajar dan faktor eksternal lainnya seperti waktu belajar, tidur, kehadiran, motivasi, dan manajemen waktu. Model ini menggunakan algoritma regresi linier.

📁 Struktur Project
notebooks/projectRasya.ipynb     # Notebook utama analisis & modeling
dataset/enhanced_student_habits_performance_dataset.csv  # Dataset yang digunakan

🧰 Tools dan Library
Python (pandas, matplotlib, seaborn, scikit-learn)
Google Colab / Jupyter Notebook
VS Code (opsional untuk dokumentasi)
GitHub (opsional untuk version control)

🔍 Langkah-langkah Analisis
Data Understanding
Menjelaskan struktur data dan variabel yang digunakan.
Data Cleaning
Menghapus missing values dan memastikan data siap untuk diproses.
Exploratory Data Analysis (EDA)
Menelusuri pola data menggunakan visualisasi dan korelasi.
Data Preparation
Memilih fitur dan memisahkan data training dan testing.
Model Building
Menggunakan regresi linier untuk memprediksi nilai ujian.
Evaluasi Model
Menggunakan metrik seperti MSE dan R² Score untuk menilai performa.
📈 Hasil Model
Model regresi linier menghasilkan metrik sebagai berikut:
R² Score: 0.62
Artinya model mampu menjelaskan sekitar 62% variasi nilai ujian mahasiswa. Cukup baik, mengingat banyak faktor lain yang tidak diukur.
Mean Squared Error (MSE): 18.9
Nilai MSE menunjukkan seberapa besar rata-rata kesalahan kuadrat prediksi.
d Error (RMSE): 4.34
RMSE menyatakan kesalahan rata-rata prediksi dalam satuan nilai ujian.

🧠 Insight dari Analisis
Faktor yang paling memengaruhi nilai ujian:
Waktu belajar per hari
Tingkat kehadiran
Manajemen waktu
Motivasi
Visualisasi menunjukkan bahwa semakin tinggi waktu belajar & kehadiran, semakin tinggi nilai ujian.

✅ Kesimpulan
Model ini dapat digunakan untuk memperkirakan potensi nilai ujian berdasarkan kebiasaan belajar. Walaupun sederhana, model ini menunjukkan bahwa kebiasaan harian seperti belajar, tidur, dan kehadiran punya dampak nyata terhadap hasil belajar.





