# Analisis Sentimen Lembaga Survei pada Pemilihan Presiden 2024 Menggunakan _Support Vector Machine_

_Repository_ ini berisi implementasi penelitian **analisis sentimen terhadap lembaga survei** pada Pemilihan Presiden Indonesia 2024 menggunakan data _tweet_ dari media sosial X (Twitter). Metode yang digunakan meliputi **pelabelan sentimen berbasis _lexicon_**, **ekstraksi fitur TF-IDF**, dan **klasifikasi _Multi-Class Support Vector Machine_ (SVM)**.

---

## _Tools_ & _Library_
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- wordcloud  
- imbalanced-learn

---

## Cara Menjalankan Program
1. _Clone repository_:
```bash
git clone https://github.com/imleesya/Analisis-Sentimen-Lembaga-Survei.git
```
2. _Install library_ yang dibutuhkan:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn wordcloud imbalanced-learn
```
3. Jalankan _notebook_ utama:
```text
Syntax/syntax_skripsi.ipynb
```
_Notebook_ tersebut mencakup _preprocessing data_, pelabelan sentimen, ekstraksi fitur, pelatihan model, serta evaluasi hasil.

---

## Output
- Visualisasi distribusi sentimen
- _Word cloud_ berdasarkan lembaga survei dan polaritas sentimen
- Perbandingan performa model SVM kernel _Linear_ dan RBF
- Hasil evaluasi model klasifikasi

---

## Catatan
_Repository_ ini disusun sebagai pendukung penelitian skripsi dan dapat digunakan sebagai referensi untuk penelitian analisis sentimen, _text mining_, dan klasifikasi teks berbahasa Indonesia.
