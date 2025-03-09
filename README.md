# Proyek Analisis Data: Bike Sharing Dataset 

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pola peminjaman sepeda berdasarkan berbagai faktor seperti musim, cuaca, dan waktu dalam sehari. Analisis dilakukan dengan menggunakan dataset "Bike Sharing Dataset".

## Informasi Pengguna
- **Nama**: [Input Nama]
- **Email**: [Input Email]
- **ID Dicoding**: [Input Username]

## Struktur Analisis
1. **Menentukan Pertanyaan Bisnis**
   - Bagaimana tren penggunaan sepeda berdasarkan musim?
   - Faktor apa yang paling mempengaruhi jumlah peminjaman sepeda?

2. **Import Semua Packages/Library**
   - `pandas`: Untuk manipulasi data.
   - `matplotlib.pyplot`: Untuk membuat visualisasi data.
   - `seaborn`: Untuk analisis visual lebih lanjut.

3. **Data Wrangling**
   - **Gathering Data**: Memuat dataset dari file CSV.
   - **Assessing Data**: Meninjau informasi dataset.
   - **Cleaning Data**: Membersihkan data jika diperlukan.

4. **Exploratory Data Analysis (EDA)**
   - **Explore Data**: Menampilkan beberapa baris data.
   - **Visualization & Explanatory Analysis**: Membuat grafik tren peminjaman berdasarkan musim dan analisis korelasi faktor yang mempengaruhi peminjaman.

5. **Analisis Lanjutan (Opsional)**
   - Menyelidiki faktor-faktor tambahan yang berpengaruh.

6. **Kesimpulan**
   - Jumlah penyewaan sepeda menunjukkan tren musiman yang signifikan.
   - Cuaca memiliki dampak pada jumlah peminjaman sepeda.
   - Waktu dalam sehari mempengaruhi jumlah peminjaman, dengan puncak di jam sibuk.

## Cara Menjalankan
### Jupyter Notebook
1. Pastikan telah menginstal library yang dibutuhkan:
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Jalankan Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Buka file `bike_sharing_analysis.ipynb` dan jalankan sel satu per satu.

### Streamlit di VS Code
1. Pastikan telah menginstal Streamlit:
   ```bash
   pip install streamlit
   ```
2. Jalankan aplikasi Streamlit di VS Code:
   ```bash
   streamlit run main.py
   ```

## Dataset yang Digunakan
- **day.csv**: Dataset harian untuk analisis tren penggunaan sepeda.
- **hour.csv**: Dataset per jam untuk analisis tren peminjaman berdasarkan waktu.

---

