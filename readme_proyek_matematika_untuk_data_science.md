# 📊 Matematika untuk Data Science — Portofolio Proyek/Latihan

Selamat datang di repositori proyek **Matematika untuk Data Science**! Repositori ini berisi implementasi konsep-konsep fundamental matematika, statistika, dan probabilitas dalam menyelesaikan berbagai permasalahan nyata di bidang _Data Science_ dan _Software Engineering_.

Proyek ini disusun sebagai bagian dari penyelesaian tugas komprehensif dan didokumentasikan agar mudah dipahami sebagai referensi maupun portofolio teknis.

---

## 🎯 Ringkasan Proyek

Dalam proyek ini, dilakukan eksplorasi dan implementasi kode menggunakan bahasa pemrograman Python (dalam format Jupyter Notebook `.ipynb` dan skrip `.py`) yang terbagi menjadi tiga studi kasus utama:

1. **Distribusi Probabilitas & Algoritma Naive Bayes**
2. **Matematika di Balik Sistem Rekomendasi & Pengujian A/B (A/B Testing)**
3. **Analisis Statistik & Eksperimen dalam Pengembangan Perangkat Lunak (Software Development A/B Testing)**

---

## 📂 Struktur Repositori

Berikut adalah daftar berkas yang terdapat di dalam repositori ini:

```text
├── soal_1_distribusi_dan_algoritma_naive_bayes.ipynb   # Notebook eksplorasi Distribusi & Naive Bayes
├── soal_1_distribusi_dan_algoritma_naive_bayes.py      # Skrip Python untuk Soal 1
├── soal_2_sistem_rekomendasi_ab.ipynb                  # Notebook eksplorasi Sistem Rekomendasi & A/B Testing
├── soal_2_sistem_rekomendasi_ab.py                     # Skrip Python untuk Soal 2
├── soal_3_software_dev_ab.ipynb                        # Notebook eksplorasi Software Dev A/B Testing
├── soal_3_software_dev_ab.py                           # Skrip Python untuk Soal 3
├── kriteria-2-knowledge-check-submissions.xlsx         # Dataset/evaluasi terkait pengujian kriteria
└── README.md                                           # Dokumentasi proyek
```

---

## 🧠 Detail Pembahasan & Implementasi

### 1. Distribusi Probabilitas & Algoritma Naive Bayes

- **Berkas:** `soal_1_distribusi_dan_algoritma_naive_bayes.ipynb` | `.py`
- **Fokus Utama:**
  - Memahami dan memodelkan berbagai jenis distribusi probabilitas (seperti distribusi diskrit dan kontinu) pada dataset.
  - Mengimplementasikan **Teorema Bayes** dan algoritma klasifikasi **Naive Bayes** dari dasar maupun menggunakan pustaka standar untuk memprediksi kelas target berdasarkan probabilitas fitur.

### 2. Sistem Rekomendasi & A/B Testing

- **Berkas:** `soal_2_sistem_rekomendasi_ab.ipynb` | `.py`
- **Fokus Utama:**
  - Menerapkan konsep aljabar linear dan metrik kemiripan (seperti _Cosine Similarity_ atau matriks faktorisasi) untuk membangun model **Sistem Rekomendasi**.
  - Melakukan evaluasi performa dan dampak perubahan sistem menggunakan metode **A/B Testing** serta uji hipotesis statistik untuk memastikan signifikansi hasil.

### 3. Eksperimen A/B dalam Pengembangan Perangkat Lunak

- **Berkas:** `soal_3_software_dev_ab.ipynb` | `.py`
- **Fokus Utama:**
  - Menganalisis metrik performa dan perilaku pengguna dalam siklus pengembangan perangkat lunak (_Software Development_).
  - Merancang eksperimen terkontrol (_A/B Testing_), menghitung ukuran sampel, serta melakukan uji signifikansi (_p-value_, _confidence interval_) untuk pengambilan keputusan berbasis data (_data-driven decision making_).

---

## 🛠️ Teknologi & Pustaka yang Digunakan

- **Bahasa Pemrograman:** Python 3.x
- **Lingkungan Pengembangan:** Jupyter Notebook
- **Pustaka Utama:**
  - `NumPy` & `Pandas` — Manipulasi data dan komputasi numerik/matriks.
  - `SciPy` & `Statsmodels` — Pengujian hipotesis, distribusi statistik, dan analisis probabilitas.
  - `Scikit-Learn` — Pemodelan _Machine Learning_ (Naive Bayes, metrik evaluasi).
  - `Matplotlib` & `Seaborn` — Visualisasi data dan distribusi statistik.

---

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori ini ke komputer lokal Anda:**

   ```bash
   git clone https://github.com/username-anda/nama-repositori-anda.git
   cd nama-repositori-anda
   ```

2. **Instal pustaka yang diperlukan:**
   Pastikan Anda sudah menginstal Python, lalu jalankan perintah berikut untuk menginstal dependensi umum:

   ```bash
   pip install numpy pandas scipy scikit-learn matplotlib seaborn jupyter openpyxl
   ```

3. **Jalankan Notebook atau Skrip:**
   - Untuk melihat analisis interaktif dan visualisasi, buka file `.ipynb` menggunakan Jupyter Notebook atau VS Code:
     ```bash
     jupyter notebook
     ```
   - Atau jalankan langsung melalui terminal menggunakan file `.py`:
     ```bash
     python soal_1_distribusi_dan_algoritma_naive_bayes.py
     ```
