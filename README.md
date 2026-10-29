# Praktikum - Clustering dengan K-Means
Mata Kuliah: Pembelajaran Mesin (INF62325) Nama: Alfiah Lutfi Sabilah NIM: 2488010032

## Ringkasan
Praktikum ini membahas clustering menggunakan algoritma K-Means untuk mengelompokkan data tanpa label. Kegiatan yang dilakukan meliputi scaling, penentuan jumlah cluster menggunakan Metode Elbow, pengelompokan data dengan K-Means, evaluasi menggunakan Silhouette Score, serta interpretasi karakteristik setiap cluster.

## Isi Repositori
PM_P9_Alfiah Lutfi Sabilah_2488010032.ipynb : notebook praktikum

## Temuan Utama
- Metode Elbow digunakan untuk membantu menentukan jumlah cluster yang optimal berdasarkan perubahan nilai inertia.
- Algoritma K-Means dengan K=3 digunakan untuk mengelompokkan data berdasarkan usia, pendapatan, dan skor belanja.
- Silhouette Score digunakan untuk mengevaluasi kualitas pengelompokan. Nilai yang mendekati 1 menunjukkan cluster yang semakin terpisah dengan baik.
- Pada pengujian data ini, Silhouette Score dengan scaling sebesar 0.4863, sedangkan tanpa scaling sebesar 0.5229.
- Hasil pengujian menunjukkan bahwa Silhouette Score tanpa scaling lebih tinggi pada dataset ini. Hal tersebut menunjukkan bahwa scaling tidak selalu menghasilkan nilai silhouette yang lebih tinggi karena hasilnya dipengaruhi oleh karakteristik dan skala data.
- Scatter plot usia dan skor belanja digunakan untuk memvisualisasikan persebaran data berdasarkan cluster.
