# Prediksi Risiko Gagal Bayar Pinjaman

Proyek ini membangun model prediktif untuk mengidentifikasi pemohon pinjaman yang cenderung gagal bayar.

## 📊 Data
- Sumber: Risiko Gagal Bayar Kredit Rumah
- Baris: 307.511
- Fitur yang digunakan: 13 fitur numerik terpilih dengan nilai hilang yang rendah

## 🧠 Model
- Algoritma: Regresi Logistik
- Praproses: Imputasi Median + StandardScaler
- Penyetelan: GridSearchCV (C=0,1, penalti=l1)
- ROC AUC: 0,76
