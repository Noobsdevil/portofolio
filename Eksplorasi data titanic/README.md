# Eksplorasi Data Titanic

## Analisis Distribusi

Awalnya, dilakukan visualisasi distribusi **usia penumpang** menggunakan histogram dan boxplot berdasarkan **kelas penumpang (pclass)**. Visualisasi ini membantu memahami bagaimana umur penumpang tersebar di setiap kelas.

Selanjutnya, visualisasi diubah untuk melihat **distribusi kelas berdasarkan jenis kelamin**.  
Perubahan yang dilakukan antara lain:
- Mengganti `histplot` menjadi `countplot`.
- Mengubah sumbu-x dari `age` menjadi `sex`.
- Menambahkan parameter `hue="pclass"` agar setiap jenis kelamin dapat dibandingkan menurut kelas penumpangnya.

Dengan perubahan ini, grafik memperlihatkan **perbandingan jumlah penumpang pria dan wanita pada setiap kelas**, sehingga pola distribusi kelas berdasarkan jenis kelamin dapat terlihat lebih jelas.
