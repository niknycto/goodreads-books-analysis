# goodreads-books-analysis
Analisis eksploratif dataset buku Goodreads (CRISP-DM)

# 📚 Goodreads Books Analysis

Analisis eksploratif terhadap dataset buku Goodreads untuk menemukan insight seputar popularitas buku, penulis, bahasa, dan rating.

---

## 🎯 Tujuan
Menganalisis tren dan pola pada dataset buku Goodreads untuk memahami faktor-faktor yang berkaitan dengan popularitas dan rating buku.

---

## 📂 Dataset
- **Sumber:** [Goodreads-books by Soumik](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) (Kaggle)
- **Jumlah data:** ±11.000 buku
- **Fitur utama:** Title, Authors, Average Rating, ISBN, Language Code, Number of Pages, Ratings Count, Text Reviews Count

---

## 🔍 Tahapan Analisis
Proyek ini mengikuti metodologi **CRISP-DM**:

1. 🔍 **Data Understanding** — memahami struktur dan karakteristik data
2. 🧹 **Data Cleaning** — menangani missing values, format kolom, dan data tidak konsisten
3. 📊 **Outlier Handling** — deteksi dan penanganan outlier menggunakan boxplot & IQR
4. 📈 **Exploratory Data Analysis (EDA)** — analisis distribusi rating, buku terpopuler, bahasa, dan penulis
5. 💡 **Conclusion & Business Insight** — merangkum temuan dan implikasi bisnis

---

## 💡 Hasil & Insight Utama

- 📊 **Distribusi Rating** — mayoritas buku memiliki rating 3.75–4.25 (rata-rata 3.93), menunjukkan kecenderungan rating positif dari pembaca
- 🏆 **Buku Terpopuler** — *Twilight* menjadi buku dengan jumlah ratings terbanyak (4.6 juta), diikuti dominasi seri Harry Potter
- 🌍 **Bahasa Buku** — 94% buku dalam dataset berbahasa Inggris, menunjukkan bias dataset terhadap pasar Inggris
- ✍️ **Penulis Produktif** — P.G. Wodehouse merupakan penulis paling produktif dengan 40 buku
- 📏 **Halaman vs Rating** — tidak ditemukan korelasi signifikan (r = 0.067) antara jumlah halaman dan rating buku

### Business Insight
- Platform rekomendasi buku sebaiknya tidak menjadikan jumlah halaman sebagai faktor penentu rekomendasi
- Strategi pemasaran berbasis franchise/series terbukti efektif membangun engagement jangka panjang
- Diperlukan diversifikasi data buku non-Inggris untuk analisis yang lebih representatif secara global

### Keterbatasan
Dataset tidak memiliki kolom genre sehingga analisis genre tidak dapat dilakukan. Dataset juga didominasi buku berbahasa Inggris yang dapat membatasi generalisasi temuan.

---

## 🛠️ Tools & Library
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)

---

## 👩‍💻 Author
**Nikmatul Khasanah**
[![GitHub](https://img.shields.io/badge/GitHub-niknycto-181717?style=flat&logo=github)](https://github.com/niknycto)
