# DeepRetina: Klasifikasi Gambar Retina dengan Ensemble DenseNet & EfficientNet

## Deskripsi

DeepRetina adalah proyek deep learning untuk klasifikasi gambar retina ke dalam 5 kelas menggunakan model ensemble yang menggabungkan DenseNet121 dan EfficientNetB0. Model ini memanfaatkan transfer learning dan teknik regularisasi untuk meningkatkan akurasi dan generalisasi pada data medis retina.

## Fitur Utama

- **Ensemble CNN:** Kombinasi DenseNet121 & EfficientNetB0.
- **Transfer Learning:** Pretrained ImageNet weights.
- **Penanganan Ketidakseimbangan Kelas:** Class weighting otomatis.
- **Pipeline Efisien:** Pembagian data otomatis, prefetching, dan augmentasi.
- **Evaluasi Komprehensif:** Confusion matrix, classification report, ROC-AUC.
- **Callback Lanjutan:** Early stopping, learning rate scheduler, model checkpoint.

## Cara Replikasi

### 1. Clone Repository

```bash
git clone https://github.com/username/ml-deep-retina.git
cd ml-deep-retina
```

### 2. Install Dependencies

Disarankan menggunakan virtual environment.

```bash
python -m venv venv
source venv/bin/activate  # atau venv\Scripts\activate di Windows
pip install -r requirements.txt
```

### 3. Download Dataset

Dataset yang digunakan: [ichwanakmaluddin/augment-d2](https://www.kaggle.com/datasets/ichwanakmaluddin/augment-d2)

- Download dataset dari Kaggle dan ekstrak ke folder `augment-d2/augmented_dataset_2` sesuai struktur notebook.

### 4. Jalankan Notebook

Buka dan jalankan `DeepRetina_Densenet_Effnet_v2.ipynb` secara berurutan.

- Pastikan path dataset sudah sesuai.
- Training, evaluasi, dan inferensi dapat dilakukan langsung di notebook.

### 5. Inferensi Model

Setelah training selesai, model dapat digunakan untuk prediksi gambar retina baru menggunakan cell inferensi di notebook.

## Requirements

Lihat file [requirements.txt](requirements.txt) untuk daftar dependensi.

## Catatan

- Notebook ini dapat dijalankan di Google Colab atau Kaggle Notebook.
- Pastikan GPU tersedia untuk training lebih cepat.

---
