![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-orange)

# 🌟 High-Dimensional Taxonomy Classification using IPCA, KNN, and Naive Bayes

Proyek ini merupakan implementasi machine learning untuk melakukan klasifikasi class taxonomy pada data berdimensi tinggi menggunakan metode **Incremental Principal Component Analysis (IPCA)** sebagai teknik reduksi dimensi, serta membandingkan performa algoritma **K-Nearest Neighbor (KNN)** dan **Naive Bayes (NB)** dalam proses klasifikasi.

Penelitian ini bertujuan untuk menganalisis efektivitas metode klasifikasi pada data berdimensi tinggi serta mengevaluasi pengaruh reduksi dimensi terhadap performa model machine learning dalam bidang bioinformatika.

---

# 🎯 Fokus Penelitian

Metode yang digunakan dalam penelitian ini meliputi:

## 🔹 Incremental Principal Component Analysis (IPCA)
Digunakan untuk:
- Mereduksi dimensi data berdimensi tinggi
- Mengurangi kompleksitas komputasi
- Mempertahankan informasi penting dari dataset

## 🔹 K-Nearest Neighbor (KNN)
Digunakan sebagai metode klasifikasi berbasis kedekatan jarak antar data.

## 🔹 Naive Bayes (NB)
Digunakan sebagai metode klasifikasi probabilistik berbasis Teorema Bayes.

---

# 🚀 Tujuan Project

- Mengimplementasikan metode Incremental PCA (IPCA) pada data berdimensi tinggi
- Membandingkan performa algoritma KNN dan Naive Bayes
- Mengevaluasi hasil klasifikasi menggunakan metrik evaluasi machine learning
- Menganalisis pengaruh reduksi dimensi terhadap performa model
- Mengembangkan pipeline machine learning untuk klasifikasi taxonomy
- Mengimplementasikan pendekatan machine learning pada data bioinformatika

---

# 📂 Dataset

Dataset yang digunakan merupakan dataset biological sequence berdimensi tinggi yang digunakan untuk proses klasifikasi class taxonomy.

Dataset telah melalui beberapa tahapan preprocessing, antara lain:
- Data cleaning
- Sequence preprocessing
- Feature extraction
- Feature scaling
- Reduksi dimensi menggunakan IPCA

📌 Format dataset:
- Biological sequence data
- Taxonomy/class label

📎 Dataset tersedia pada folder `data/`

---

# 🛠️ Teknologi yang Digunakan

| Teknologi | Deskripsi |
|---|---|
| Python | Bahasa pemrograman utama untuk analisis data dan machine learning |
| Pandas | Manipulasi dan preprocessing data |
| NumPy | Operasi numerik dan komputasi array |
| Scikit-learn | Implementasi IPCA, KNN, dan Naive Bayes |
| Matplotlib | Visualisasi data dan evaluasi model |
| Seaborn | Visualisasi confusion matrix dan grafik evaluasi |
| BioPython | Pengolahan dan analisis biological sequence |
| Jupyter Notebook | Lingkungan pengembangan dan eksperimen model |

---

# 🧠 Metodologi Penelitian

Tahapan penelitian yang dilakukan:

1. Data Cleaning  
2. Data Preprocessing  
3. Feature Extraction  
4. Feature Scaling  
5. Reduksi Dimensi menggunakan IPCA  
6. Pemodelan menggunakan:
   - K-Nearest Neighbor (KNN)
   - Naive Bayes (NB)
7. Evaluasi Model  
8. Perbandingan Performa Model

---

# 📡 Pipeline Penelitian

Diagram berikut menunjukkan alur proses klasifikasi taxonomy pada data berdimensi tinggi menggunakan metode IPCA, KNN, dan Naive Bayes.

![Pipeline Penelitian](images/pipeline.png)

---
# 📊 Evaluasi Model

Model dievaluasi menggunakan beberapa metrik machine learning, antara lain:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

---

# 🏆 Hasil Penelitian

Hasil eksperimen menunjukkan bahwa metode IPCA mampu membantu proses reduksi dimensi pada dataset berdimensi tinggi sehingga meningkatkan efisiensi klasifikasi.

Performa model menunjukkan bahwa:
- Model KNN memiliki performa klasifikasi yang lebih stabil pada data berdimensi tinggi
- Naive Bayes memiliki waktu komputasi yang lebih cepat
- IPCA membantu mengurangi kompleksitas fitur tanpa mengurangi performa model secara signifikan

📌 Hasil evaluasi divisualisasikan menggunakan confusion matrix, radar chart, dan grafik variance IPCA.

---

# 📷 Visualisasi

## 🔹 Confusion Matrix Gaussian Naive Bayes
![Confusion Matrix GNB](images/confusion_matrix_gnb.png)

## 🔹 Confusion Matrix K-Nearest Neighbor
![Confusion Matrix KNN](images/confusion_matrix_knn.png)

## 🔹 Visualisasi Variance IPCA
![IPCA Variance](images/ipca.png)

## 🔹 Radar Chart Macro Multiclass
![Radar Chart](images/radar_chart.png)

---

# 📁 Struktur Project

```text
high-dimensional-taxonomy-classification/
│
├── data/
├── images/
├── notebook/
│   ├── 01_preprocessing.ipynb
│   └── 02_modeling_knn_nb.ipynb
│
├── requirements.txt
└── README.md
```

---

# 🧑‍💻 Cara Menjalankan Project

## 1. Clone Repository

```bash
git clone https://github.com/sains-data/high-dimensional-taxonomy-classification.git
```

---

## 2. Masuk ke Direktori Project

```bash
cd high-dimensional-taxonomy-classification
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Jalankan Jupyter Notebook

```bash
jupyter notebook
```

Kemudian jalankan notebook:
- `01_preprocessing.ipynb`
- `02_modeling_knn_nb.ipynb`

---

# 🚀 Future Improvement

Pengembangan lebih lanjut yang dapat dilakukan:

- Implementasi metode deep learning untuk klasifikasi taxonomy
- Optimasi hyperparameter menggunakan GridSearchCV
- Eksplorasi metode reduksi dimensi lainnya seperti t-SNE dan UMAP
- Penggunaan dataset biological sequence yang lebih besar
- Implementasi deployment model berbasis web

---

# 👥 Author

- Elia Meylani Simanjuntak

---

# 📫 Kontak

- LinkedIn: www.linkedin.com/in/elia-meylani
- GitHub: github.com/eliameylani

---

# 🙏 Ucapan Terima Kasih

Terima kasih kepada:
- Dosen pembimbing yang telah memberikan arahan dan bimbingan selama penelitian
- Seluruh pihak yang mendukung proses penelitian dan pengembangan project ini
- Program Studi Sains Data ITERA

---

# 🔗 Tautan Penting

- 📄 Repository GitHub: https://github.com/eliameylani/high-dimensional-taxonomy-classification
