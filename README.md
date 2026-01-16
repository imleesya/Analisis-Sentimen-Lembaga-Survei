# Analisis Sentimen Lembaga Survei pada Pemilihan Presiden 2024 Menggunakan _Support Vector Machine_

Repository ini berisi implementasi penelitian **analisis sentimen terhadap lembaga survei** pada Pemilihan Presiden Indonesia 2024 menggunakan data _tweet_ dari media sosial X (Twitter). Metode yang digunakan meliputi **pelabelan sentimen berbasis _lexicon_**, **ekstraksi fitur TF-IDF**, dan **klasifikasi _Multi-Class Support Vector Machine_ (SVM)**.

---

## Tools & Library
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- wordcloud  
- imbalanced-learn

---

## Cara Menjalankan Program
1. Clone repository:
```bash
git clone https://github.com/imleesya/Analisis-Sentimen-Lembaga-Survei.git
```
2. Install library yang dibutuhkan:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn wordcloud imbalanced-learn
```
3. Jalankan notebook utama:
```text
Syntax/syntax_skripsi.ipynb
```
Notebook tersebut mencakup preprocessing data, pelabelan sentimen, ekstraksi fitur, pelatihan model, serta evaluasi hasil.

---

## Output
- Visualisasi distribusi sentimen
- Word cloud berdasarkan lembaga survei dan polaritas sentimen
- Perbandingan performa model SVM kernel Linear dan RBF
- Hasil evaluasi model klasifikasi

---

## Catatan
Repository ini disusun sebagai pendukung penelitian skripsi dan dapat digunakan sebagai referensi untuk penelitian analisis sentimen, text mining, dan klasifikasi teks berbahasa Indonesia.
