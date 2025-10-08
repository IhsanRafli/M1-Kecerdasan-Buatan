# M1-Kecerdasan-Buatan
Clastering Data coffee Menggunakan beberapa Algoritma 

# ☕ Coffee Sales Classification Project

## Problem Statement
Penjualan kopi harian menunjukkan variasi yang dipengaruhi oleh waktu, metode pembayaran, serta jenis kopi yang dipilih pelanggan. Namun, tanpa analisis prediktif, sulit untuk memahami pola pembelian dan memprediksi jenis kopi yang kemungkinan besar dibeli pada waktu tertentu.  
Proyek ini bertujuan membangun model **klasifikasi jenis kopi** berdasarkan data transaksi harian. Nilai bisnisnya adalah membantu manajer kedai kopi dalam **meningkatkan stok, penjadwalan barista, dan strategi promosi** berdasarkan waktu dan perilaku pelanggan.

## Project Scope

### In-Scope
- Analisis eksplorasi data transaksi kopi (EDA).  
- Pra-pemrosesan data: encoding, scaling, dan splitting.  
- Pelatihan model **Random Forest**, **SVM**, dan **XGBoost**.  
- Optimasi hyperparameter menggunakan **GridSearchCV**.  
- Visualisasi perbandingan akurasi antar-model.  

### Out-of-Scope
- Integrasi model ke sistem POS nyata.  
- Penggunaan data real-time atau prediksi berbasis streaming.  
- Analisis faktor ekonomi makro (harga bahan, musim, dll).
- 
## Ethical & Privacy Considerations
Dataset ini tidak berisi data pribadi sensitif, namun tetap berpotensi menimbulkan **risiko bias perilaku pelanggan** jika digunakan tanpa konteks. Misalnya, model bisa disalahgunakan untuk membatasi promosi hanya pada segmen waktu tertentu, mengurangi keadilan peluang pelanggan.  
Mitigasinya: dataset hanya digunakan untuk **analisis agregat dan optimasi operasional internal**, bukan pengambilan keputusan individual. Selain itu, seluruh data pribadi (jika ada di masa depan) akan dianonimkan sebelum digunakan.

## Tools & Libraries
- Python, Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-Learn, XGBoost  
- Google Colab, GitHub, KaggleHub 


## Evaluation Metrics

| Metric | Deskripsi | Target | Baseline |
|:-------|:-----------|:--------|:----------|
| **Accuracy** | Proporsi prediksi benar terhadap total data uji. | ≥ 0.90 | 0.70 |
| **Precision / Recall / F1-score** | Digunakan untuk melihat performa tiap kelas kopi. | ≥ 0.85 | 0.60 |

Model dengan akurasi dan F1-score tertinggi akan dipilih sebagai kandidat terbaik.

