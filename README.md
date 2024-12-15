# Tugas Besar 2 IF3170 - Inteligensi Artifisial 2024/2025

## Deskripsi

Repository ini berisi implementasi algoritma pembelajaran mesin **K-Nearest Neighbors (KNN)**, **Gaussian Naive Bayes**, dan **ID3 (Iterative Dichotomiser 3)**, yang diterapkan pada dataset **UNSW-NB15**. Tujuan tugas ini adalah untuk memberikan pengalaman langsung dalam menerapkan algoritma pembelajaran mesin pada masalah nyata serta membandingkan hasil implementasi "from scratch" dengan library scikit-learn.

## Struktur Repository

- `src/` : Folder ini berisi source code implementasi algoritma dan eksperimen.
- `doc/` : Folder ini berisi laporan dalam format PDF, termasuk penjelasan teknis dan hasil eksperimen.
- `README.md` : Dokumen ini berisi panduan untuk memahami dan menjalankan proyek.

## Dataset

Dataset **UNSW-NB15** adalah kumpulan data lalu lintas jaringan yang mencakup berbagai jenis serangan siber dan aktivitas normal. Dataset dapat diakses melalui tautan berikut:
- [Dataset di Kaggle](https://www.kaggle.com/t/ddd18d90f93a47e48f8850b1f1592381)
- [UNSW Research](https://research.unsw.edu.au/projects/unsw-nb15-dataset)

## Fitur Utama

1. **Implementasi KNN (from scratch)**:
   - Mendukung parameter jumlah tetangga.
   - Mendukung 3 metrik jarak: Euclidean, Manhattan, dan Minkowski.

2. **Implementasi Gaussian Naive Bayes (from scratch)**.

3. **Implementasi ID3 (from scratch)**:
   - Mendukung pemrosesan data numerik sesuai materi kuliah.

4. **Perbandingan hasil implementasi dengan library scikit-learn**:
   - Untuk ID3, digunakan `DecisionTreeClassifier` dengan parameter `criterion='entropy'`.

5. **Model Persistence**:
   - Model dapat disimpan dan dimuat kembali dalam berbagai format seperti `.pkl` atau `.txt`.

## Setup

### Prasyarat
- Python 3.8 atau lebih baru.
- Library yang diperlukan:
  - `numpy`
  - `pandas`
  - `scikit-learn`

### ⬇️Instalasi
1. Clone repository ini:
   ```bash
   git clone https://github.com/jimlynurarif/cetjipiti.git
   ```
2. Masuk ke direktori cetjipiti:
   ```bash
   cd cetjipiti
   ```
3. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```

## 🏃‍♂️Cara Menjalankan

1. Pastikan dataset sudah disiapkan di direktori yang sesuai.
2. Jalankan notebook untuk melakukan eksperimen:
   ```bash
   jupyter notebook
   ```
3. Pilih file notebook yang ingin dijalankan

## Pembagian Tugas Kelompok

| Nama Anggota         | NIM        | Kontribusi                        |
|----------------------|------------|-----------------------------------|
| Jimly Nur Arif       | 13522123   | Implementasi ID3                  |
| Yosef Rafael Joshua  | 13522133   | Implementasi Gaussian Naive Bayes |
| Samy Muhammad Haikal | 13522151   | Implementasi KNN                  |
| Muhammad Roihan      | 13522152   | Propcessing And Splitting         |

## 🪪Lisensi

Proyek ini dilindungi oleh lisensi [MIT License](LICENSE).

## Referensi

- [The UNSW-NB15 Dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- [K-Nearest Neighbor (KNN) Algorithm](https://www.geeksforgeeks.org/k-nearest-neighbours/)
- [What Are Naïve Bayes Classifiers?](https://www.ibm.com/topics/naive-bayes)
- [Decision Trees: ID3 Algorithm Explained](https://towardsdatascience.com/decision-trees-for-classification-id3-algorithm-explained-89df76e72df1)
