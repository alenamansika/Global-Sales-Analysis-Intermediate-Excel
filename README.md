# 📊 Analisis Penjualan Global (Grafik Interaktif Intermediate Excel)

## 📌 Ringkasan Proyek
Proyek ini menganalisis data penjualan *Global E-Commerce* (2.000 transaksi) menggunakan fitur-fitur **Intermediate Excel** untuk menghasilkan visualisasi data yang dinamis dan interaktif tanpa kode (*code-free interactivity*).

## 🛠️ Fitur & Teknik Excel yang Digunakan

* **Pembersihan Data & Persiapan:** Pembersihan data transaksi mentah dan pembuatan tabel penampung dinamis (*staging tables*) di sheet `Data_Preparation`.
* **Interaktivitas Form Control:**
  * **Scroll Bar & Tombol Spinner:** Mengubah rentang tanggal (tanggal mulai, tanggal akhir, serta durasi hari) secara dinamis untuk grafik tren penjualan harian.
  * **Radio / Option Buttons:** Mengubah tampilan grafik secara instan untuk membandingkan performa kategori berdasarkan segmen pelanggan (*Consumer*, *Corporate*, *Home Office*).
* **Data Validation:** Menu *dropdown* interaktif untuk memfilter performa penjualan kategori berdasarkan wilayah (*Region*) yang dipilih.
* **Rumus & Fungsi Dinamis:** `INDIRECT`, `SORT`, `FILTER`, `SWITCH`, `UNIQUE`, dan `SORTBY` untuk agregasi data otomatis.

## 📈 Tampilan Grafik Interaktif

### 1. Grafik Penjualan Harian Dinamis (Scroll Bar & Spinner)
Menampilkan tren penjualan harian dalam rentang waktu yang fleksibel. Scroll Bar berfungsi mengatur tanggal mulai, sedangkan Spinner menentukan durasi hari, sehingga grafik dan judulnya berubah secara otomatis.
![Scroll Bar & Spinner Chart](chart1_scroll_spinner.jpeg)

### 2. Grafik Komparasi Segmen Pelanggan (Radio Button)
Membandingkan penjualan antar kategori produk berdasarkan segmen pelanggan. Saat tombol Radio Button (*Consumer*, *Corporate*, atau *Home Office*) dipilih, grafik akan memperbarui total penjualan sesuai segmen tersebut.
![Radio Button Chart](chart2_radio_button.jpeg)

### 3. Grafik Analisis Wilayah (Data Validation)
Visualisasi penjualan kategori produk yang diurutkan berdasarkan nilai penjualan untuk wilayah tertentu. Memilih wilayah dari *dropdown* Data Validation akan memperbarui grafik batang dan urutan nilainya secara otomatis.
![Data Validation Chart](chart3_data_validation.jpeg)

## 📁 Struktur Repositori
* `Global_Sales_Analysis_Intermediate_Excel.xlsx` : File kerja utama Excel.
* `Raw Data` : Dataset transaksi mentah (2.000 baris).
* `Data Preparation` : Sheet pendukung rumus dinamis & agregasi data.
* `Dynamic_Chart_FormControl` & `InteractiveChart_DataValidation` : Sheet visualisasi utama.
