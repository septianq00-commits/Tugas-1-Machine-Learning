# Tugas-1-Machine-Learning
Pada Tugas 1 ini, Anda akan bekerja dengan sebuah dataset berisi informasi mahasiswa dari berbagai program studi. Dataset ini sengaja dirancang dengan beberapa permasalahan umum dalam dunia nyata, seperti data yang hilang (missing values), inkonsistensi format data, serta tipe data kategorikal yang belum siap diproses oleh model machine learning.
Anda diharapkan dapat menerapkan langkah-langkah data preprocessing untuk menyiapkan dataset ini agar siap digunakan dalam proses pelatihan model machine learning.

Petunjuk Pengerjaan:

Kerjakan tugas1 ini secara berurutan sesuai dengan tahapan berikut:

Tahap 1: Load Dataset

• Impor library yang diperlukan

• Baca file dataset_tugas1_preprocessing.csv ke dalam DataFrame

Tahap 2: Eksplorasi Awal (EDA)

• Cek struktur dan tipe data

• Tampilkan jumlah nilai hilang per kolom

• Sajikan statistik deskriptif

Tahap 3: Menangani Missing Values

• Imputasi nilai kosong pada kolom Nilai_Akhir dan Umur dengan metode yang sesuai

Tahap 4: Normalisasi Format Tanggal

• Pastikan seluruh data pada kolom Tanggal_Ujian terkonversi ke format datetime

Tahap 5: Encoding Label

• Lakukan encoding (Label Encoding) pada kolom kategorikal: Nama, Jenis_Kelamin, Prodi, Status, Nilai_Akhir

Tahap 6: Split Data

• Bagi data menjadi data latih dan data uji (80% - 20%)

Tahap 7: Visualisasi

• Buat histogram untuk kolom Umur

• Buat grafik batang jumlah mahasiswa per Prodi

Pengumpulan:
• Simpan hasil pengerjaan Anda dalam format .ipynb (jika ingin diunggah di Tuton) dan atau ke upload filenya github dan infokan link untuk diperiksa Tutor.
