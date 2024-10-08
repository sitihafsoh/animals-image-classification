# **Proyek Klasifikasi Gambar: 10 Hewan Darat**
<br><br>

![animals5](https://github.com/user-attachments/assets/0ec3b309-6491-4f70-8eb0-99a763a76a0e)

# **Latar Belakang**

Pengenalan gambar telah mengalami kemajuan pesat dalam beberapa tahun terakhir, didorong oleh perkembangan deep learning. Kemampuan untuk mengidentifikasi objek dalam gambar secara otomatis memiliki banyak aplikasi, salah satunya adalah dalam bidang konservasi. Dataset Animals10 dari Kaggle berisi gambar dari 10 spesies hewan darat yang berbeda, menyediakan sumber daya yang berharga untuk mengembangkan model klasifikasi gambar yang kuat.

Proyek ini bertujuan untuk membangun dan mengevaluasi model machine learning yang mampu mengklasifikasikan gambar hewan dari dataset Animals10 dengan akurasi yang tinggi. Model yang berhasil akan memiliki potensi aplikasi yang luas, seperti:
- Pemantauan satwa liar: Membantu para peneliti dan konservasionis dalam melacak populasi hewan dan memahami pola migrasi mereka.
- Aplikasi edukasi: Menyediakan alat yang interaktif untuk membantu orang belajar tentang berbagai jenis hewan.
- Pariwisata: Mengembangkan aplikasi yang dapat membantu wisatawan mengidentifikasi satwa yang mereka temui di alam liar.
  
Untuk mencapai tujuan ini, akan dilakukan eksplorasi berbagai arsitektur jaringan saraf konvolusional (CNN) dan teknik augmentasi data. Selain itu, juga akan dilakukan analisis kinerja model dengan metrik akurasi.

# **Dataset**
Dataset yang digunakan dalam proyek ini adalah Animals-10, yang dapat diunduh dari Kaggle: https://www.kaggle.com/datasets/alessiocorrado99/animals10. Dataset ini berisi 10 kelas hewan darat, termasuk anjing, kucing, kuda, dan lain-lain.

| Kelas Hewan | Jumlah Gambar |
|---|---|
| Butterfly (farfalla) | 2112 |
| Cat (gatto) | 1668 |
| Chicken (gallina) | 3098 |
| Cow (mucca) | 1866 |
| Dog (cane) | 4863 |
| Elephant (elefante) | 1446 |
| Horse (cavallo) | 2623 |
| Sheep (pecora) | 1820 |
| Spider (ragno) | 4821 |
| Squirrel (scoiattolo) | 1862 |

Total dataset: 26179 gambar
