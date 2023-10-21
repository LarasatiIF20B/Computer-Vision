# Computer-Vision
**Tasks 1**
memecahkan studi kasus dan melengkapi todo sebagai berikut :
5 Change the color channel from BGR to RGB using cv2.COLOR_BGR2RGB
5 Change the color channel from BGR to Grayscale using cv2.COLOR_BGR2GRAY
10 Change the color channel from Grayscale to Binary using cv2.THRESH_BINARY
15 Plot the histogram from the original image
10 Plot the histogram from the grayscale image
10 QUESTION: What does PyTorch offer in its Max Pooling operation compared to Scikit-image?
10 Recall the block_reduce(), but with func=np.min
10 Recall the block_reduce().astype(int), but with func=np.mean
5 What is the difference between Min Pooling and Average Pooling operations?
5 Call the function apply_clahe_rgb() and pass the variable image of "photo1.jpeg"
10 QUESTION: What are the advantages of using CLAHE (instead of Max Pooling) to brighten the dark-toned image?
5 Give any file name to your new CLAHE-enhanced photo, ends with .png extension
****Tasks 2 ****
memecahkan studi kasus kan melengkapi todo sebagai berikut :
1. Pilih DenseNet sebagai model pertama untuk bereksperimen, lalu ubah jumlah neuron di
lapisan pertama dan terakhir (karena ImageNet memiliki 1.000 kelas, sedangkan MNIST hanya
memiliki 10 kelas; keduanya juga hadir dengan ukuran gambar dan saluran yang berbeda).
2. Tentukan hyperparameter dan latih modelnya (semua layer dilatih dari awal).
3. Plot performa model, baik untuk hasil pelatihan maupun validasi.
4. Sekarang, coba bekukan (freeze, tidak dilatih) beberapa bagian layer: (1) "denseblock1", (2)
"denseblock1" dan "denseblock2". Ini akan menjadi dua model terpisah.
5. Latih kembali setiap model, visualisasikan performanya, dan periksa perbedaannya.
6. BONUS: Bisakah Anda mereplikasi semua langkah di atas dengan model yang berbeda.
Kemudian memastikan setiap todo telah terisi
