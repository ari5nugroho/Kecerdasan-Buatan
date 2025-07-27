#  CNN Batik Classifier - UAS Kecerdasan Buatan

Proyek ini dibuat untuk memenuhi tugas **Ujian Akhir Semester** mata kuliah **Kecerdasan Buatan (ST045)** di Universitas Amikom Yogyakarta. Proyek menggunakan **Convolutional Neural Network (CNN)** untuk mengklasifikasikan gambar **motif batik tradisional Indonesia** secara otomatis.

##  Identitas Mahasiswa

- **Nama** : Ari Nugroho
- **NIM**  : 23.11.5796
- **Kelas**: S1 Informatika - Semester 4

##  Deskripsi Proyek

Model CNN dibuat menggunakan **6 lapisan convolution**. Dataset batik diperoleh dari repository GitHub dan diproses menggunakan augmentasi `zoom` dan `shear`.

###  Tools & Library

- Python 3
- TensorFlow / Keras
- Google Colab
- GitHub
- Matplotlib

##  Cara Menjalankan

1. Buka Google Colab:  
   [Klik untuk membuka notebook](https://colab.research.google.com/drive/1RIai_gu5b9ohMucEPsCiMEOnmApZh1rP?usp=sharing)

2. Clone dataset (otomatis di Colab):
   ```python
   !git clone https://github.com/annaamikom/dataset-batik.git

3. Jalankan seluruh sel dari atas ke bawah (Runtime > Run all)
