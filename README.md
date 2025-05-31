
Image Processing adalah aplikasi desktop GUI berbasis Python yang menyediakan beragam fitur pengolahan citra digital, deteksi wajah, face swap, dan analisis ekspresi secara real-time. Dibangun dengan kombinasi teknologi **PyQt5, OpenCV, dan Dlib**, aplikasi ini cocok untuk pembelajaran, riset, maupun demonstrasi Computer Vision tingkat lanjut.

---

## 🚀 Fitur Utama

### 📌 Operasi Dasar
- Grayscale, Brightness, Contrast, Negative
- Binerisasi: Binary, Trunc, To Zero, Invers, Otsu, Adaptive

### 📊 Histogram
- Histogram RGB & Grayscale
- Histogram Equalization

### 📐 Transformasi Geometri
- Translasi, Rotasi, Transpose
- Resize (Zoom In / Zoom Out), Crop

### 🧮 Filtering Spasial
- Mean, Median, Gaussian
- Sharpening (I–VI), Max & Min Filter

### ⚙️ Frekuensi & Konvolusi
- DFT Smoothing & Edge Detection
- Custom Kernel, Edge Detectors (Sobel, Prewitt, Robert, Canny)

### 🧱 Morfologi Citra
- Erosi, Dilasi, Opening, Closing, Skeletonizing

### 🔍 Deteksi Bentuk & Warna
- Contour & Shape Recognition (Lingkaran, Segitiga, dst)
- Color Tracking (Merah, Biru, Hijau + HSV Picker)

### 🧠 Object & Face Detection
- HaarCascade: Wajah, Mata, Mobil, Pejalan Kaki
- HOG: Histogram of Oriented Gradients

### 😎 Analisis Ekspresi & Manipulasi Wajah
- Facial Landmark (68 titik)
- Face Swap (2 gambar atau real-time)
- Yawn Detection (deteksi menguap otomatis)

---

## 🛠️ Instalasi & Menjalankan

### 1. Install Dependensi
```bash
pip install opencv-python opencv-contrib-python dlib pyqt5 imutils matplotlib scikit-image
````

### 2. Jalankan Aplikasi

```bash
python kode.py
```

> Pastikan file berikut tersedia di direktori:
>
> * `GUI.ui`
> * `shape_predictor_68_face_landmarks.dat`
> * `haarcascade_frontalface_default.xml`
> * Gambar: `boeing.jpg`, `traktor.jpg`, `trump.jpg`, dsb.

---

## 💻 Teknologi yang Digunakan

* [x] Python 3.x
* [x] PyQt5 (GUI)
* [x] OpenCV (Image & Video Processing)
* [x] Dlib (Facial Landmark Detection)
* [x] Matplotlib (Histogram & Visualisasi)
* [x] Skimage (Fitur HOG)

---

## 📸 Screenshot GUI (opsional)

> Tambahkan di sini gambar tampilan aplikasi.

---

## 👤 Pengembang

* **Nama**: Didik Indrayana
* **Instansi**: Universitas Muhammadiyah Sukabumi
* **Konsentrasi**: Computer Vision, Digital Transformation, AI Engineering

---

## 📜 Lisensi

Aplikasi ini bebas digunakan untuk keperluan **edukasi**, **penelitian**, dan **demonstrasi teknologi** non-komersial.

---

## 🤝 Kontribusi

Silakan fork, laporkan issue, atau kembangkan fitur baru!

```
