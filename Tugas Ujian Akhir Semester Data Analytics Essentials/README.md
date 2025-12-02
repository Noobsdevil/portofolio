---

# **README**

## **Cara Menggunakan Workflow KNIME**

1. **Buka KNIME Analytics Platform.**
2. Pergi ke **File → Import KNIME Workflow…**
3. Pilih folder yang berisi proyek ini.
4. Setelah di-import, cari workflow-nya di KNIME Explorer.
5. Klik kanan node pertama (biasanya **File Reader**) → **Execute**, lalu
   klik kanan di bagian kosong workflow → **Execute All**.
6. Pastikan file dataset (`.csv`) berada di folder yang sesuai.
   Jika tidak, buka File Reader dan **ganti path** ke file CSV Anda.
7. Setelah proses selesai, klik kanan node output terakhir untuk melihat tabel atau visualisasi.

---

## **Apa yang Dilakukan Workflow Ini**

Workflow ini melakukan rangkaian pemrosesan data, yaitu:

* Membaca dataset dari file CSV
* Membersihkan nilai hilang (missing values)
* Menghapus baris yang tidak relevan atau salah
* Menambahkan kolom baru untuk kebutuhan analisis
* Melakukan pengelompokan data menggunakan **Pivoting**
* Menghitung jumlah kematian dan total penumpang per kategori
* Menghitung **persentase kematian** untuk setiap kategori
* Menghasilkan tabel ringkasan berisi:

  * **Kategori** (misalnya: male, female, young)
  * **Total penumpang**
  * **Total kematian**
  * **Persentase kematian**
  * **Dan lain lain**

---

## **Output Akhir**

Workflow ini menghasilkan:

* Tabel ringkasan yang sudah dikelompokkan berdasarkan kategori
* Perhitungan **% kematian per kategori**
* Visualisasi 

---

## 📊 Ringkasan Hasil Analisis

File KNIME ini menampilkan berbagai informasi penting mengenai **penumpang Titanic**, khususnya terkait **kelangsungan hidup (survival)** berdasarkan umur dan gender. Analisis mencakup:
* **Jumlah penumpang yang masih hidup** serta **jumlahnya** berdasarkan:

  * Umur
  * Gender (pria & wanita)
<img width="1384" height="296" alt="image" src="https://github.com/user-attachments/assets/e95c0f0f-0093-4d0c-bf0b-9138553ffde8" />

* **Jumlah penumpang yang masih hidup** serta **persentasenya** berdasarkan:

  * Umur
  * Gender (pria & wanita)
<img width="1393" height="296" alt="image" src="https://github.com/user-attachments/assets/1349ee27-c5ff-4b0d-852a-e690acf71bdc" />

* **Persentase penumpang yang selamat berdasarkan rentang umur** tertentu.
<img width="1395" height="283" alt="image" src="https://github.com/user-attachments/assets/76676503-ae9c-4b96-8d77-9a2e26942fbd" />

* **Jumlah penumpang yang selamat** dalam kategori:

  * Anak-anak (di bawah 18 tahun)
  * Pria
  * Wanita
<img width="1384" height="290" alt="image" src="https://github.com/user-attachments/assets/cb558709-f171-4101-bfc5-640d267a93e0" />

* **Jumlah total penumpang awal** dalam dataset.
<img width="1350" height="298" alt="image" src="https://github.com/user-attachments/assets/53dc0260-5f9b-44c4-936c-435e68884c77" />

* **Jumlah penumpang yang meninggal** serta **persentasenya** berdasarkan:

  * Umur
  * Gender
<img width="1378" height="289" alt="image" src="https://github.com/user-attachments/assets/3d410d90-29db-4dfb-b381-297a1ba01af2" />

* **Jumlah penumpang yang meninggal** dalam kategori:

  * Anak-anak
  * Pria
  * Wanita
<img width="1385" height="290" alt="image" src="https://github.com/user-attachments/assets/eb6e3fee-d17b-45f4-a75f-cb4b3c1352e2" />

* **Persentase kematian untuk setiap kategori**:

  * Pria
  * Wanita
  * Anak-anak
<img width="1389" height="288" alt="image" src="https://github.com/user-attachments/assets/0a5790e3-466f-4a21-ba75-f90e0eb94236" />

* **Persentase kematian setiap kategori (pria, wanita, dan anak-anak) pada setiap kelas (1st, 2nd, 3rd class).**
<img width="1373" height="261" alt="image" src="https://github.com/user-attachments/assets/2b9befa1-a2fb-4619-b30b-26628e9b13d7" />
