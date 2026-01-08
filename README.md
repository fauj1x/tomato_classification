# tomato_classification

DESKRIPSI PROYEK / PROJECT DESCRIPTION
------------------------------------------------------------
(ID) Proyek ini adalah sebuah sistem berbasis Python yang 
dirancang untuk mengklasifikasikan citra tomat ke dalam 
beberapa kategori tertentu (seperti tingkat kematangan atau 
jenis) menggunakan pendekatan Deep Learning. Proyek ini 
memanfaatkan Jupyter Notebook untuk proses eksperimen, 
pelatihan model, dan evaluasi hasil.

(EN) This project is a Python-based system designed to 
classify tomato images into specific categories (such as 
ripeness levels or types) using a Deep Learning approach. 
The project utilizes Jupyter Notebook for experimentation, 
model training, and results evaluation.
------------------------------------------------------------

TEKNOLOGI YANG DIGUNAKAN
------------------------------------------------------------
- Bahasa Pemrograman: Python 3.x
- Library Utama:
  * TensorFlow/Keras (untuk pembangunan model neural network)
  * NumPy (untuk manipulasi array dan data numerik)
  * Matplotlib/Seaborn (untuk visualisasi data dan hasil)
  * OpenCV/PIL (untuk pemrosesan citra)
- Lingkungan Pengembangan: Jupyter Notebook

STRUKTUR REPOSITORI
------------------------------------------------------------
- Tomat_cls.ipynb  : Notebook utama yang berisi seluruh alur 
                     kerja mulai dari pemuatan data, 
                     preprocessing, arsitektur model, hingga 
                     pengujian.
- README.md        : File informasi dasar repositori.

ALUR KERJA TEKNIS
------------------------------------------------------------
1. Pemuatan Data: Mengambil dataset gambar tomat dari 
   direktori lokal atau cloud.
2. Preprocessing: Melakukan resize gambar, normalisasi pixel, 
   dan augmentasi data untuk meningkatkan akurasi model.
3. Arsitektur Model: Menggunakan Convolutional Neural 
   Network (CNN) untuk mengekstraksi fitur dari gambar tomat.
4. Pelatihan (Training): Melatih model menggunakan optimizer 
   seperti Adam dan loss function Categorical Crossentropy.
5. Evaluasi: Mengukur performa model menggunakan metrik 
   Accuracy, Precision, dan Recall melalui confusion matrix.

5. CARA PENGGUNAAN
------------------------------------------------------------
1. Pastikan Python dan library yang diperlukan sudah terpasang.
2. Buka file `Tomat_cls.ipynb` menggunakan Jupyter Notebook 
   atau Google Colab.
3. Siapkan dataset tomat pada folder yang ditentukan di dalam 
   notebook.
4. Jalankan seluruh sel (cells) secara berurutan untuk 
   melihat proses pelatihan dan hasil klasifikasi.

============================================================
