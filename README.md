# Analisis-Tekstur-Telur-Menggunakan-GLCM-LBP-dengan-Klasifikasi-SVM

Alur Pengerjaan dari Penelitian :
1. Melakukan Analisis RGB pada dataset yang asli yang sudah di crop sebelumnya tanpa melakukan perubahan ke fitur grayscale. Menggunakan dataset [drive](https://drive.google.com/open?id=1LIy1qGC7-g3PdHkcSLTQtPslFbICIdVq&usp=drive_copy) ini. Setelah itu menyimpan hasil analisis RGB pada file .csv yang diberi nama "Analisis_DataRGB(fix).csv".
2. Melakukan Preprocessing dan menyimpannya pada folder yang diberi nama "Preprocessing_Dataset_Skripsi".
3. Melakukan Ekstraksi Fitur GLCM dan LBP menggunakan dataset hasil preprocessing. Menggunakan Dataset pada [drive](https://drive.google.com/drive/folders/13mzfwg1X6legX-OdfCMIDQHvRUkFU66n?usp=sharing) ini. Lalu hasil dari ekstraksi fitur glcm dan lbp ini akan disimpan pada file .csv yang diberi nama "Hasil_Ekstraksi_Telur.csv".
4. Dilakukan normalisasi pada dataset "Hasil_Ekstraksi_Telur.csv".
5. Dilakukan T-Test pada dataset hasil ekstraksi yang sudah dinormalisasi yang dapat dilihat pada dataset "Ekstraksi Fitur (T-Test)-FINAL.csv"
6. Melakukan Klasifikasi menggunakan Algoritma SVM pada data hasil ekstraksi GLCM dan LBP yang sudah dinormalisasi dan disimpan pada file .csv "Hasil_Ekstraksi_Telur_Normalized.csv".






© 2025 Yolanda Ester Berliana Ritonga.
