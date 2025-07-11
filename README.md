# Analisis Sentimen Aplikasi Wondr by BNI

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pengguna aplikasi Wondr by BNI menggunakan Natural Language Processing, Lexicon-based Labeling, dan Teknik TF-IDF.

## Struktur Folder

- `datasets/` : Berisi dataset hasil scraping dan pembersihan data ulasan aplikasi.
  - `ulasan_wondr_bni.csv` : Dataset utama ulasan aplikasi.
  - `clean_ulasan_wondr_bni.csv` : Dataset yang sudah dibersihkan.
  - `scraping_code.ipynb` : Notebook untuk proses scraping data ulasan.
- `modeling/` : Berisi notebook untuk proses analisis dan modeling machine learning.
  - `Analisis_Sentimen_Aplikasi_Wondr_by_BNI.ipynb` : Notebook utama analisis sentimen.
- `requirements.txt` : Daftar dependensi Python yang dibutuhkan.

## Cara Menjalankan Proyek

1. **Clone repository** (jika dari GitHub):
   ```bash
   git clone <repo-url>
   ```
2. **Install dependensi**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan notebook**:
   Buka file notebook di folder `datasets/` atau `modeling/` menggunakan Jupyter Notebook atau VS Code.

## Dependensi Utama

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- nltk

(Lihat `requirements.txt` untuk daftar lengkap)

## Alur Proyek

1. **Scraping Data**: Mengambil data ulasan aplikasi dari sumber terkait.
2. **Pembersihan Data**: Membersihkan data dari duplikasi, karakter tidak perlu, dsb.
3. **Analisis Sentimen**: Melakukan analisis sentimen menggunakan machine learning.
4. **Visualisasi**: Menampilkan hasil analisis dalam bentuk grafik.

## Kontributor

- Nama Anda di sini

---

_Proyek ini dibuat untuk pembelajaran dan pengembangan machine learning pada analisis sentimen aplikasi._
