# Menghilangkan Outlier dengan Metode IQR

## Latar Belakang
Di sini saya memiliki sebuah dataset **TGM 2020–2023_eng**.  
Tujuan saya adalah menghilangkan *outlier* dari dataset tersebut agar analisis lebih akurat dan grafik yang dihasilkan lebih representatif.

## Metode
Metode **Interquartile Range (IQR)** digunakan untuk mendeteksi dan menghapus outlier pada data.  
Biasanya, metode ini menggunakan **kuartil** (Q1 dan Q3) untuk menentukan batas bawah dan batas atas.  

Namun, dalam kasus ini saya menggunakan **persentil ke-15 dan ke-85** sebagai batasan.  
Dengan cara ini, saya dapat fokus pada bagian data yang paling relevan dan menampilkannya dalam grafik.

## Kesimpulan
Setelah menerapkan metode ini, saya berhasil menghilangkan outlier dan hanya menampilkan data antara persentil ke-15 dan ke-85.  
Hasilnya, grafik menjadi lebih bersih, mudah dibaca, dan lebih merepresentasikan tren utama dari dataset.
