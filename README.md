# Analisis Kebakaran DKI Jakarta 2013

Proyek ini berisi analisis data kejadian kebakaran di Provinsi DKI Jakarta pada tahun 2013. Fokus utama dari notebook ini adalah memahami pola kejadian kebakaran, mengevaluasi karakteristik data, serta membangun model prediksi sederhana untuk estimasi kerugian.

## Tujuan

- Menganalisis distribusi kejadian kebakaran berdasarkan wilayah, penyebab, dan dampak.
- Membersihkan dan mempersiapkan data agar siap diproses.
- Melakukan visualisasi data untuk memahami pola kejadian.
- Membangun model regresi linear untuk memprediksi taksiran kerugian.
- Mengevaluasi performa model menggunakan metrik seperti MAE, RMSE, dan R2.

## Struktur File

- `data-kejadian-kebakaran-di-provinsi-dki-jakarta-tahun-2013-komponen-data.xls.csv` — dataset utama yang digunakan.
- `UTS-PM-KELAS-202431019-Rafael Ramadhan Indrawan.ipynb` — notebook analisis dan modeling.
- `README.md` — dokumentasi proyek.

## Dataset

Dataset berisi informasi kejadian kebakaran di DKI Jakarta tahun 2013, termasuk aspek seperti:

- tanggal dan wilayah kejadian
- jenis objek yang terbakar
- penyebab kebakaran
- jumlah unit, SDM, jiwa, dan KK terdampak
- luas area kejadian
- taksiran kerugian
- kronologi kejadian

## Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Alur Analisis

1. Memuat dataset CSV ke dalam DataFrame.
2. Melakukan pembersihan data pada kolom `taksiran_kerugian` dan `luas_area_kejadian`.
3. Melakukan visualisasi data untuk melihat distribusi kerugian dan dampak kejadian.
4. Menyaring outlier agar hasil analisis lebih representatif.
5. Menentukan fitur numerik dan kategorikal.
6. Menggunakan `ColumnTransformer` untuk preprocessing data.
7. Melatih model `LinearRegression`.
8. Mengevaluasi hasil model dengan metrik MAE, RMSE, dan R2.

## Cara Menjalankan

Pastikan Python dan library yang dibutuhkan sudah terinstall.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Lalu buka notebook dengan:

```bash
jupyter notebook
```

Pilih file:

```text
UTS-PM-KELAS-202431019-Rafael Ramadhan Indrawan.ipynb
```

## Hasil yang Diharapkan

Notebook ini menghasilkan:

- visualisasi kejadian kebakaran
- analisis dampak terhadap jumlah jiwa dan kerugian
- data yang sudah diproses dan siap digunakan untuk pemodelan
- evaluasi performa model prediksi kerugian

## Catatan

Proyek ini merupakan tugas/analisis akademik yang bertujuan untuk mengeksplorasi data kebakaran dan menerapkan teknik machine learning dasar untuk prediksi kerugian.
