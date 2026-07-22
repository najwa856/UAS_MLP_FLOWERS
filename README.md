# 🌸 UAS Pengolahan Citra Digital
## Klasifikasi Citra Bunga Menggunakan Multi-Layer Perceptron (MLP)

Repository ini dibuat untuk memenuhi tugas **Ujian Akhir Semester (UAS)** Mata Kuliah **Pengolahan Citra Digital**.

---

## 👤 Identitas Mahasiswa

| Keterangan | Informasi |
|------------|------------|
| **Nama** | Najwa Shalsabila |
| **NIM** | 24146031 |
| **Program Studi** | Sistem Informasi |
| **Fakultas** | Teknik |
| **Universitas** | Abulyatama |
| **Mata Kuliah** | Pengolahan Citra Digital |
| **Dosen Pengampu** | Teuku Rizky Noviandy, S.Kom., M.Kom. |

---

## 📖 Deskripsi

Proyek ini mengimplementasikan algoritma **Multi-Layer Perceptron (MLP)** untuk melakukan klasifikasi citra bunga menggunakan dataset **Flowers Recognition**. Model dibangun menggunakan Python dan pustaka Scikit-learn dengan beberapa tahap preprocessing seperti resize gambar, normalisasi, ekstraksi fitur menggunakan PCA, pembagian data latih dan data uji, proses pelatihan model, hingga evaluasi performa.

---

## 🌼 Dataset

Dataset yang digunakan adalah **Flowers Recognition Dataset** yang terdiri dari lima kelas bunga:

- 🌼 Daisy
- 🌼 Dandelion
- 🌹 Rose
- 🌻 Sunflower
- 🌷 Tulip

---

## ⚙️ Tahapan Pengolahan Data

1. Import Library
2. Membaca Dataset
3. Resize Citra (64 × 64 piksel)
4. Normalisasi Nilai Piksel
5. Flatten Image
6. Principal Component Analysis (PCA)
7. Split Dataset (80% Training dan 20% Testing)
8. Pelatihan Model MLP
9. Prediksi Data Uji
10. Evaluasi Model

---

## 🧠 Algoritma

Model yang digunakan pada proyek ini adalah **Multi-Layer Perceptron (MLP)** dengan konfigurasi:

- Activation Function : ReLU
- Optimizer : Adam
- Hidden Layer : 32 Neuron
- Early Stopping : Enabled
- Random State : 24146031

---

## 📊 Evaluasi Model

Evaluasi dilakukan menggunakan metrik:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## 💻 Tools dan Library

- Python
- NumPy
- Matplotlib
- Pillow (PIL)
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📂 Struktur Repository

```text
📦 UAS-Pengolahan-Citra-Digital-MLP
 ├── UAS_Pengolahan_Citra_Digital.ipynb
 ├── Laporan_UAS.pdf
 ├── README.md
```

---

## 🎯 Tujuan

Mengimplementasikan metode **Multi-Layer Perceptron (MLP)** untuk mengklasifikasikan lima jenis bunga berdasarkan citra digital serta mengevaluasi performa model menggunakan metrik klasifikasi.

---

## ©️ Copyright

**© 2026 - 24146031 | Sistem Informasi**

Repository ini dibuat untuk keperluan akademik pada Mata Kuliah **Pengolahan Citra Digital**.
