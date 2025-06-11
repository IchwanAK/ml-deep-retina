
# DeepRetina: Klasifikasi Gambar Retina dengan Ensemble DenseNet & EfficientNet

DeepRetina adalah proyek *deep learning* yang berfokus pada pengembangan model kecerdasan buatan untuk klasifikasi gambar retina. Model ini dirancang untuk mengidentifikasi tingkat keparahan retinopati diabetik ke dalam 5 kelas berbeda. Menggunakan pendekatan *ensemble* dengan menggabungkan kekuatan arsitektur DenseNet121 dan EfficientNetB0, proyek ini memanfaatkan *transfer learning* dan berbagai teknik *regularization* canggih untuk mencapai akurasi tinggi dan generalisasi yang kuat pada data medis yang kompleks.

## 🚀 Fitur Utama

-   **Ensemble CNN:** Menggabungkan kekuatan arsitektur *Convolutional Neural Network* (CNN) terkemuka: DenseNet121 dan EfficientNetB0 untuk performa superior.
-   **Transfer Learning:** Memanfaatkan *pretrained weights* dari ImageNet untuk mempercepat konvergensi dan meningkatkan akurasi, bahkan dengan data yang terbatas.
-   **Penanganan Ketidakseimbangan Kelas:** Mengimplementasikan *class weighting* otomatis untuk mengatasi masalah *imbalanced dataset* pada klasifikasi medis.
-   **Pipeline Efisien:** Dilengkapi dengan *pipeline* pemrosesan data yang efisien, termasuk pembagian data otomatis, *prefetching*, dan teknik *data augmentation* yang ekstensif.
-   **Evaluasi Komprehensif:** Menyediakan metrik evaluasi mendalam seperti *confusion matrix*, *classification report*, dan kurva ROC-AUC untuk analisis performa model yang akurat.
-   **Callback Lanjutan:** Menggunakan *callback* canggih seperti *early stopping*, *learning rate scheduler*, dan *model checkpoint* untuk optimasi proses *training*.

## 📋 Table of Contents

-   [Teknologi](#teknologi)
-   [Getting Started](#getting-started)
-   [Requirements](#requirements)
-   [Catatan](#catatan)
-   [Tim Pengembang](#tim-pengembang)
-   [Support](#support)

## 🛠 Teknologi

-   **Deep Learning Framework:** TensorFlow & Keras
-   **Model Arsitektur:** DenseNet121, EfficientNetB0 (Ensemble)
-   **Bahasa Pemrograman:** Python
-   **Data Manipulation:** NumPy, Pandas
-   **Data Visualisasi:** Matplotlib, Seaborn
-   **Alat Pengembangan:** Jupyter Notebook / Google Colab / Kaggle Notebook

## 🚀 Getting Started

### 1. Clone Repository

```bash
git clone [https://github.com/username/ml-deep-retina.git](https://github.com/username/ml-deep-retina.git)
cd ml-deep-retina
````

### 2\. Install Dependencies

Sangat disarankan untuk menggunakan *virtual environment* untuk mengelola dependensi proyek.

```bash
python -m venv venv
source venv/bin/activate   # Untuk macOS/Linux
# atau `venv\Scripts\activate` untuk Windows
pip install -r requirements.txt
```

### 3\. Download Dataset

Dataset yang digunakan untuk proyek ini dapat diunduh dari Kaggle: [ichwanakmaluddin/augment-d2](https://www.kaggle.com/datasets/ichwanakmaluddin/augment-d2).

  - Pastikan untuk mengunduh dataset dan mengekstraknya ke folder `augment-d2/augmented_dataset_2` agar sesuai dengan struktur path yang digunakan dalam *notebook*.

### 4\. Jalankan Notebook

Buka dan jalankan *notebook* utama proyek, `DeepRetina_Densenet_Effnet_v2.ipynb`, secara berurutan dari awal hingga akhir.

  - Verifikasi bahwa *path* dataset telah disesuaikan dengan lokasi ekstrak dataset Anda.
  - Proses *training* model, evaluasi performa, dan inferensi (prediksi) dapat dilakukan langsung di dalam *notebook* ini.

### 5\. Inferensi Model

Setelah proses *training* selesai dan model telah disimpan, Anda dapat menggunakannya untuk melakukan prediksi pada gambar retina baru. Bagian inferensi model tersedia di dalam *notebook* untuk kemudahan pengujian.

## 📜 Requirements

Daftar lengkap dependensi proyek ini dapat dilihat pada file [requirements.txt](https://www.google.com/search?q=requirements.txt).

## 📝 Catatan

  - *Notebook* ini dirancang agar kompatibel dan dapat dijalankan dengan mudah di lingkungan komputasi awan seperti Google Colab atau Kaggle Notebook.
  - Untuk mempercepat proses *training* model, sangat disarankan untuk menggunakan GPU.

## 👥 Tim Pengembang

Proyek ini dikembangkan oleh tim yang sama yang mengerjakan web app Deep Retina:

#### 💻 **Fullstack Developer Team**

  - **Naufal Haidar Nityasa** - Lead Frontend & Backend Developer
    *Student ID: FC183D5Y0361*

  - **Taufiq Hidayatullah** - Frontend & Backend Developer
    *Student ID: FC183D5Y1868*

  - **Dinda Lolyta Buma Lestari** - Frontend & Backend Developer
    *Student ID: FC183D5X2401*

#### 🤖 **Machine Learning Engineering Team**

  - **Satriatama Putra** - Machine Learning Engineer & Project Leader
    *Student ID: MC299D5Y2065*
    🏆 Role: Ketua Tim & ML Model Development

  - **Ichwan Akmaluddin** - Machine Learning Engineer
    *Student ID: MC299D5Y1451*

  - **Cahya Abdurrahman** - Machine Learning Engineer
    *Student ID: MC299D5Y1469*

## 📞 Support

Jika Anda menemui masalah selama replikasi, memiliki pertanyaan, atau ingin memberikan umpan balik:

  - Anda dapat membuat [Issue](https://github.com/its-nflll/deep-retina/issues)
  - Email: info@deepretina.id

-----

⭐ **Jangan ragu untuk memberikan bintang pada repositori ini jika proyek ini bermanfaat\!**
