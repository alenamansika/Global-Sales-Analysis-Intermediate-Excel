# 📊 Global Sales Analysis (Intermediate Excel Interactive Charts)

## 📌 Project Overview
Proyek ini menganalisis data penjualan **Global E-Commerce (2.000 transaksi)** menggunakan fitur-fitur **Intermediate Excel** untuk menghasilkan visualisasi data yang dinamis dan interaktif tanpa menggunakan kode (*code-free interactivity*).

## 🛠️ Excel Features & Techniques Used

* **Data Preparation:** Pembersihan data transaksi mentah dan pembuatan *staging tables* dinamis pada sheet `Data_Preparation`.
* **Form Control Interactivity:**
  * **Spinner Button & Scroll Bar:** **Spinner** berfungsi menentukan tanggal mulai (*start date*), sedangkan **Scroll Bar** menentukan rentang/durasi hari untuk grafik tren penjualan harian.
  * **Radio / Option Buttons:** Mengubah data grafik secara instan untuk membandingkan performa penjualan antar kategori berdasarkan segmen pelanggan (*Consumer*, *Corporate*, *Home Office*).
* **Data Validation:** Menu *dropdown* interaktif untuk memfilter performa penjualan sub-kategori berdasarkan wilayah (*Region*) yang dipilih.
* **Formulas & Dynamic Functions:** `INDIRECT`, `SORT`, `FILTER`, `SWITCH`, `UNIQUE`, dan `SORTBY` untuk agregasi data dinamis.

## 📈 Interactive Charts Showcase

### 1. Dynamic Daily Sales Chart (Spinner & Scroll Bar)
Menampilkan tren penjualan harian dalam rentang waktu yang fleksibel. Tombol **Spinner** digunakan untuk menentukan tanggal mulai, sedangkan **Scroll Bar** mengatur durasi hari, sehingga grafik dan judulnya ter-update secara otomatis.
![Scroll Bar & Spinner Chart](chart1_scroll_spinner.jpeg)

### 2. Segment Comparison Chart (Radio Button)
Membandingkan penjualan antar kategori produk berdasarkan segmen pelanggan. Saat Radio Button (*Consumer*, *Corporate*, atau *Home Office*) dipilih, grafik akan memperbarui total penjualan sesuai segmen tersebut secara otomatis.
![Radio Button Chart](chart2_radio_button.jpeg)

### 3. Regional Analysis Chart (Data Validation)
Visualisasi penjualan sub-kategori produk yang diurutkan berdasarkan nilai penjualan untuk wilayah tertentu. Memilih wilayah dari *dropdown* Data Validation akan memperbarui grafik batang dan urutan nilainya dari batas atas hingga bawah secara otomatis.
![Data Validation Chart](chart3_data_validation.jpeg)

## 📁 Repository Structure
* `Global_Sales_Analysis_Intermediate_Excel.xlsx` : File kerja utama Excel.
* `Raw Data` : Dataset transaksi mentah (2.000 baris).
* `Data Preparation` : Sheet pendukung rumus dinamis & agregasi data.
* `Dynamic_Chart_FormControl` & `InteractiveChart_DataValidation` : Sheet visualisasi utama.
