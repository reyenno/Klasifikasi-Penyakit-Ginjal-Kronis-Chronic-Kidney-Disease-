# Chronic Kidney Disease Prediction (Machine Learning)

Project ini merupakan implementasi **Machine Learning** untuk memprediksi **Chronic Kidney Disease (CKD)** menggunakan data klinis pasien.  
Project ini dibuat sebagai pembelajaran **Machine Learning end-to-end**.

---

## Deskripsi Project

Chronic Kidney Disease (CKD) adalah penyakit ginjal kronis yang membutuhkan deteksi dini.  
Dengan Machine Learning, Project ini bertujuan untuk membangun dan membandingkan beberapa **model Machine Learning klasifikasi** dalam memprediksi **Chronic Kidney Disease (CKD)** berdasarkan data klinis pasien.
Secara khusus, tujuan dari project ini adalah:
- Memahami alur kerja Machine Learning secara end-to-end
- Mempelajari preprocessing data medis
- Mengimplementasikan beberapa model klasifikasi
- Membandingkan performa model berdasarkan metrik evaluasi
- Menentukan model yang paling optimal untuk kasus CKD
---


## Model Machine Learning yang Digunakan

Project ini menggunakan beberapa algoritma Machine Learning untuk membandingkan performa prediksi, yaitu:

---

### Decision Tree (DT)

**Decision Tree** adalah model yang bekerja dengan cara membuat struktur pohon keputusan berdasarkan fitur-fitur pada data.

**Karakteristik:**
- Mudah dipahami dan divisualisasikan
- Tidak membutuhkan scaling data
- Cocok untuk data dengan hubungan non-linear

**Tujuan penggunaan DT:**
- Menjadi baseline model yang mudah diinterpretasikan
- Melihat bagaimana aturan keputusan terbentuk dari data medis
- Membantu memahami faktor-faktor yang berpengaruh terhadap CKD

---

### Logistic Regression (LR)

**Logistic Regression** merupakan model statistik yang digunakan untuk klasifikasi biner, dalam project ini digunakan untuk memprediksi `ckd` atau `notckd`.

**Karakteristik:**
- Model sederhana dan efisien
- Cocok untuk data dengan hubungan linear
- Memberikan output probabilitas

**Tujuan penggunaan LR:**
- Sebagai model baseline yang ringan dan cepat
- Membandingkan performa model linear dengan model non-linear
- Mengukur pengaruh setiap fitur terhadap kemungkinan CKD

---

### Naive Bayes (NB)

**Naive Bayes** adalah model probabilistik yang menggunakan Teorema Bayes dengan asumsi bahwa setiap fitur saling independen.

**Karakteristik:**
- Sangat cepat dan ringan
- Bekerja dengan baik pada dataset kecil hingga menengah
- Tahan terhadap noise pada data

**Tujuan penggunaan NB:**
- Melihat performa model probabilistik pada data medis
- Membandingkan kecepatan dan akurasi dengan model lain
- Menjadi alternatif model sederhana namun efektif

---

## Evaluasi Model

Setiap model dievaluasi menggunakan beberapa metrik, antara lain:
- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, dan F1-Score**

Hasil evaluasi digunakan untuk:
- Membandingkan performa antar model
- Menentukan model terbaik
- Menganalisis kelebihan dan kekurangan masing-masing algoritma

---

## Insight yang Diharapkan

Dari project ini diharapkan dapat diperoleh insight seperti:
- Model mana yang paling cocok untuk prediksi CKD
- Pengaruh preprocessing terhadap performa model
- Trade-off antara interpretabilitas dan akurasi model

---

## Cara Install & Menjalankan Project
### Pastikan Install Depedency
Library yang digunakan dalam project ini antara lain:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter
  
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```
---

### Clone Repository
```bash
git clone https://github.com/reyenno/Klasifikasi-Penyakit-Ginjal-Kronis-Chronic-Kidney-Disease-.git
cd Klasifikasi-Penyakit-Ginjal-Kronis-Chronic-Kidney-Disease-
```

### Jalankan Project
Jalankan jupyter notebook dan buka file chronic_kidney_disease.ipynb

## Authors
Muhammad Reyenno R.S.
Muhammad Andhika M.
I Made Dwi Wiryawan R.
