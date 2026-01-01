Prediksi Dropout Mahasiswa (XGBoost)

Proyek ini membangun sistem prediksi risiko dropout mahasiswa menggunakan algoritma XGBoost dan diimplementasikan dalam aplikasi web berbasis Streamlit.

Model dilatih menggunakan dataset Predict Students' Dropout and Academic Success dari UCI Machine Learning Repository dengan data akademik dan demografis mahasiswa.

Metode
Algoritma: XGBoost
Jenis Masalah: Klasifikasi biner (Graduate / Dropout)
Evaluasi: Accuracy, Precision, Recall, F1-Score

Fitur Utama:
Admission grade
Age at enrollment
Gender
Tuition fees up to date
Debtor
Data akademik semester 1 dan 2


Aplikasi dibangun menggunakan Streamlit untuk memprediksi status mahasiswa berdasarkan input data yang diberikan pengguna.

pip install -r requirements.txt
streamlit run app.py
