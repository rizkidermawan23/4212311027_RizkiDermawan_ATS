# 4212311027_RizkiDermawan_ATS
Kesimpulan Asesmen Pemrograman Klasifikasi Karakter Tulisan Tangan...
Asesmen ini bertujuan untuk menguji kemampuan Anda dalam membangun dan mengevaluasi sistem klasifikasi karakter tulisan tangan menggunakan teknik Computer Vision dan Machine Learning.
Tujuan Utama...
1.Ekstraksi Fitur: Menggunakan metode Histogram of Oriented Gradients (HOG) untuk mengubah citra karakter menjadi vektor fitur yang diskriminatif.
2.Klasifikasi: Menggunakan Support Vector Machine (SVM) sebagai model klasifikasi.
3.Penanganan Data: Melakukan sampling seimbang pada data latih (total 13.000 sampel, 500 sampel per kelas dari 26 kelas).
4.Evaluasi: Menggunakan metode validasi silang yang ketat, yaitu Leave-One-Out Cross-Validation (LOOCV), dan menampilkan metrik kinerja utama (confusion matrix, accuracy, precision, dan F1-score).
5.Optimasi: Melakukan tuning parameter pada HOG dan SVM untuk mencapai performa klasifikasi terbaik.
