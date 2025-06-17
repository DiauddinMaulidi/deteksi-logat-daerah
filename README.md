# 🗣️ Pengolahan Audio - Deteksi Asal Daerah Berdasarkan Logat Bahasa dengan Machine Learning

Penelitian ini merupakan implementasi deep learning berbasis keras untuk mendeteksi **asal daerah seseorang berdasarkan logat bicaranya**. Model dilatih menggunakan dataset audio berbahasa Indonesia yang diekstrak menggunakan teknik MFCC (Mel-Frequency Cepstral Coefficients) untuk diambil polanya, kemudian dianalisis untuk mengidentifikasi ciri khas fonetik/logat dari beberapa wilayah di Indonesia.

---

### 🎯 Tujuan Proyek

Meningkatkan kemampuan teknologi dalam memahami variasi bahasa daerah di Indonesia dan mengembangkan sistem klasifikasi logat otomatis yang dapat diaplikasikan untuk:
- Sistem pengenalan suara
- Asisten virtual berbasis lokal
- Kajian linguistik dan sosiolinguistik

### ⚙️ Teknologi & Library yang Digunakan

- Python 3.12
- NumPy
- Librosa (untuk ekstraksi fitur audio)
- keras (klasifikasi)
- Matplotlib (visualisasi)
- Jupyter Notebook

## Requirements
Program ini menggunakan bahasa pemrograman Python versi 3.12 dan dikembangkan dalam sistem operasi Windows.

Instal library yang dibutuhkan yaitu: numpy, librosa, ipython, tensorflow, keras, matplotlib:

```bash
$ pip install numpy
$ pip install librosa
$ pip install ipython
$ pip install tensorflow
$ pip install keras
$ pip install matplotlib

## Tahapan Program
Secara umum tahapan dalam program ini yaitu pengumpulan data, ekstraksi ciri masing-masing data, proses training hasil ekstraksi ciri untuk pengenalan pola, build model, dan testing data kemudian evaluasi.
![Image](https://github.com/user-attachments/assets/5c66e88e-6f8c-4050-8503-76627f61b6e8)






