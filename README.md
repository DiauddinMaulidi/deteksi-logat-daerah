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
```

## Tahapan Program
Secara umum tahapan dalam program ini yaitu pengumpulan data, ekstraksi ciri masing-masing data, proses training hasil ekstraksi ciri untuk pengenalan pola, build model, dan testing data kemudian evaluasi.
![Image](https://github.com/user-attachments/assets/5c66e88e-6f8c-4050-8503-76627f61b6e8)

Dataset terdiri dari file audio berdurasi pendek, dikumpulkan dari penutur dengan logat khas dari beberapa daerah Indonesia. Dataset ini telah diproses menjadi fitur MFCC, yang digunakan sebagai input untuk model.

## 🎯 Evaluasi
Model dievaluasi menggunakan:
Penelitian ini berhasil membangun sebuah model klasifikasi berbasis Deep Learning dengan Keras untuk mendeteksi asal daerah penutur berdasarkan logat berbicara. Data audio dari beberapa wilayah dianalisis menggunakan MFCC (Mel-Frequency Cepstral Coefficients) untuk mengekstrak fitur suara utama, yang kemudian dijadikan input ke dalam model neural network. Selama proses pelatihan dan evaluasi, model menunjukkan performa yang kurang baik, terdapat beberapa kesalahan klasifikasi pada kelas tertentu. Akurasi yang dihasilkan adalah 66%

## 📈 Saran
saran dalam pengembangan selanjutnya adalah:
a. Perluasan dataset dengan lebih banyak variasi penutur dan logat dari berbagai daerah di Indonesia.\n
b. Peningkatan kualitas audio dan preprocessing (misalnya, penghilangan noise).
c. Eksperimen dengan arsitektur model lain seperti LSTM atau CNN khusus audio.
d. Evaluasi menggunakan f1-score dan recall per kelas untuk mengukur lebih adil kinerja di setiap jenis logat.




