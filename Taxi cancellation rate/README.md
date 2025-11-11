

---

## 🚖 Analisis Kasus Pembatalan Taksi

Proyek analisis data berbasis **KNIME** yang mengeksplorasi tren pemesanan dan pembatalan taksi.
Dataset dibersihkan (mengganti nilai yang hilang, memformat tanggal) dan dianalisis untuk menghitung **tingkat pembatalan harian**, lalu divisualisasikan menggunakan **diagram garis (Line Plot)**.
Hasil menunjukkan bahwa tingkat pembatalan berfluktuasi dari waktu ke waktu, dengan lonjakan yang terlihat pada tanggal-tanggal tertentu.

---

### 📂 Dataset

**File:** `Taxi-cancellation-case.csv`
Berisi informasi mengenai data pemesanan taksi, termasuk:

* Tanggal pemesanan
* Detail lokasi penjemputan dan tujuan
* Status pembatalan (`Car_Cancellation`)

---

### 🧹 Pembersihan Data

Dilakukan menggunakan **KNIME Analytics Platform**:

* Menghapus atau mengganti nilai yang hilang dengan `0` dan `"Unknown"`
* Mengonversi kolom `from_date` dari string ke format tanggal (`M/d/yy`)
* Memastikan tipe data konsisten antara kolom numerik dan kategorikal

---

### 📊 Analisis

Tujuan: **Menemukan tingkat pembatalan per tanggal**

Langkah-langkah yang dilakukan:

1. Mengelompokkan data berdasarkan `from_date`
2. Menghitung rata-rata dari `Car_Cancellation` untuk mendapatkan tingkat pembatalan harian
3. Memvisualisasikan tren menggunakan **Line Plot**

---

### 🖼️ Pratinjau

<img width="1248" height="249" alt="image" src="https://github.com/user-attachments/assets/9cf78102-8510-4e58-a537-3a7dc720df85" />

---

### 📈 Hasil & Temuan

* Rata-rata tingkat pembatalan **berfluktuasi dari waktu ke waktu**
* Beberapa tanggal menunjukkan **lonjakan signifikan**, kemungkinan dipengaruhi oleh faktor eksternal seperti lonjakan permintaan atau pola jadwal tertentu
* Grafik garis membantu menyoroti pola umum dalam keandalan layanan taksi

---

### 💾 Berkas yang Diekspor

* `TaxiAnalysis.csv` — dataset yang telah dibersihkan dengan tingkat pembatalan harian
* `Taxi_Cancellation_Analysis.knwf` — berkas workflow KNIME

---

### 🔧 Alat yang Digunakan

* **KNIME Analytics Platform**

  * CSV Reader
  * Missing Value
  * String to Date&Time
  * GroupBy
  * Line Plot



