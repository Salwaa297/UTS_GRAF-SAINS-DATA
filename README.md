# UTS_GRAF-SAINS-DATA
Repository ini berisi dokumentasi dan implementasi Ujian Tengah Semester (UTS) mata kuliah Graf Sains Data. Proyek ini menggunakan dataset RetailRocket E-commerce untuk membangun graf interaksi pengguna dan produk serta menerapkan metode rekomendasi berbasis kemiripan.

# Identitas
Nama: Putri Sofiyatus Salwa

Kelas: 2024A

NIM: 24031554112

Mata Kuliah: Graf Sains Data

**Deskripsi Proyek**

Proyek berfokus pada pemodelan data e-commerce dalam bentuk graf menggunakan Neo4j, dilanjutkan dengan analisis menggunakan Vector Space Model (VSM), cosine similarity, dan metode K-Nearest Neighbors (KNN) untuk menghasilkan rekomendasi item.

**Dataset**

Dataset yang digunakan adalah RetailRocket E-commerce Dataset, yang berisi catatan interaksi pengguna terhadap item, seperti melihat produk (view) dan menambahkan produk ke keranjang (add to cart).

Dataset asli events.csv tidak disertakan langsung dalam repository GitHub karena ukuran file. Sebagai gantinya, data yang digunakan untuk proses analisis telah dibagi menjadi data training (P1) dan testing (P2).

Link Drive Dataset Training dan Testing: https://drive.google.com/drive/folders/1lBJAyotkfxHmo5INhczSLUQau3qvhtU7?usp=sharing 

Dataset tambahan: category_tree.csv


**Isi Repository**

UTS_GRAF.ipynb: Notebook berisi implementasi kode, pengolahan data, analisis graf, VSM, cosine similarity, dan rekomendasi KNN.

requirements.txt: Daftar dependensi Python yang diperlukan untuk menjalankan kode.

category_tree.csv: Data hierarki kategori produk dari dataset RetailRocket.

README.md: Dokumentasi proyek dan informasi dataset.

**Teknologi yang Digunakan**

1. Python

2. Pandas

3. Neo4j

4. Jupyter Notebook

5. Vector Space Model (VSM)

6. Cosine Similarity

7. K-Nearest Neighbors (KNN)
