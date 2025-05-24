# PROJECT FIKTI GROUP 4

# Data Koleksi Buku: Pengembangan Diri & Fiksi Lokal

## 📌 Deskripsi

Project ini bertujuan untuk menganalisis data koleksi buku, khususnya kategori Pengembangan Diri dan Fiksi Lokal, guna menemukan pola dan insight yang berguna, seperti preferensi pembaca, distribusi genre, dan potensi rekomendasi buku.

## 📁 Struktur Project

- `notebooks/model.ipynb` – Notebook utama berisi eksplorasi data dan pemodelan
- `dataset/book_collection_dataset.csv` – Dataset utama yang dianalisis

## 🧰 Tools

- Python (pandas, sklearn, matplotlib, numpy)
- Google Colab Notebook
- GitHub

## 📈 Hasil Model

Model regresi linier menghasilkan sebagai berikut:

- R² Score: 1.0 → Model mampu menjelaskan 100% variasi dari target, yang secara teori menunjukkan performa sempurna. Namun, ini juga dapat menjadi indikasi adanya overfitting atau data leakage.
- MAE (Mean Absolute Error): Nilai kesalahan rata-rata sangat kecil terhadap data asli, menunjukkan prediksi sangat dekat dengan data aktual.
- RMSE (Root Mean Squared Error): Nilai kesalahan kuadrat juga sangat kecil, memperkuat dugaan bahwa hasil prediksi sangat mendekati nilai sesungguhnya.
