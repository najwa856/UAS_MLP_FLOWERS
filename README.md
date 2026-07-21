# Klasifikasi Citra Bunga Menggunakan Multi-Layer Perceptron (MLP)

Proyek ini dibuat untuk memenuhi tugas Ujian Akhir Semester (UAS) mata kuliah Pengolahan Citra Digital / Machine Learning.

## 👤 Identitas
* **Nama Lengkap:** [Najwa Shalsabila]
* **NIM:** 24146031
* **Dataset:** Flowers Recognition (5 Kelas: daisy, dandelion, rose, sunflower, tulip)

---

## ⚙️ Alur Kerja (Workflow)
1. **Preprocessing Data:** Resizing gambar ke 64x64 piksel, flattening, dan normalisasi nilai piksel (0-1).
2. **Data Splitting:** Pembagian dataset 80% Training dan 20% Testing dengan `random_state` berbasis NIM (24146031).
3. **Pemodelan:** `MLPClassifier` dengan 2 Hidden Layers (128 dan 64 neuron).

---

## 📊 Hasil Evaluasi Model
* **Accuracy:** 43.63%
* **Precision:** 43.88%
* **Recall:** 43.63%
* **F1-Score:** 43.47%
