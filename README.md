# Face-Recognition

Repository ini merupakan program untuk deteksi wajah (face recognition) menggunakan metode Eigenfaces. Pada repository ini terdapat beberapa file penting, yaitu:

1. **README.md** — berisi instruksi untuk menjalankan program.
2. **Tutorial_Computer_Vision_1.ipynb** — merupakan notebook Jupyter yang berisi kode untuk membangun dan menjalankan program face recognition.
3. **eigenface_pipeline.pkl** — file model hasil training menggunakan metode PCA (Principal Component Analysis).
4. **Folder images/** — berisi dataset gambar wajah yang akan digunakan untuk proses pengenalan.

## Cara Menjalankan Program

1. Clone repository ini ke lokal:

   ```bash
   git clone https://github.com/nasy984/Face-Recognition.git
   cd Face-Recognition
2. Pastikan semua dependensi sudah terpasang
     ```bash
   pip install numpy opencv-python scikit-learn matplotlib
3. Buka dan jalankan file Tutorial_Computer_Vision_1.ipynb menggunakan Jupyter Notebook atau Google Colab.
4. Run semua sel pada notebook ipynb

Keterangan tambahan 
- Jika ingin menggunakan dataset gambar baru, tambahkan gambar wajah ke dalam folder images/ dengan format yang sesuai.
- Model eigenface_pipeline.pkl bisa digunakan langsung atau diperbarui sesuai kebutuhan.
