# 🧠 Prediksi Tumor Otak dengan Convolutional Neural Network (CNN)

Proyek ini bertujuan untuk memprediksi atau mengklasifikasikan tumor otak dari citra medis menggunakan model Deep Learning berbasis Convolutional Neural Network (CNN). Dataset yang digunakan adalah citra MRI yang telah dilabeli.

## ✨ Fitur
- ✅ Klasifikasi tumor otak (Normal vs Tumor)
- 🤖 Implementasi CNN menggunakan Python + TensorFlow/Keras
- 📊 Evaluasi model menggunakan akurasi dan confusion matrix

## 📂 Struktur Folder

TumorOtak_CNN/
├── dataset/              # Folder dataset gambar MRI
├── models/               # Folder untuk menyimpan model yang telah dilatih
├── TumorOtak_CNN.ipynb   # Notebook utama
├── README.md

⚠️ **Catatan Penting:**  
Pastikan path folder dataset dan folder models di dalam kode sesuai dengan alamat path di perangkat masing-masing. Contoh penyesuaian di dalam kode:

```python
dataset_path = "/path/ke/folder/dataset/"
model_save_path = "/path/ke/folder/models/model_tumor.h5"
