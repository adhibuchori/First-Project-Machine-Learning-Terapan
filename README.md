# First-Project-Machine-Learning-Terapan
Final Project of Machine Learning Terapan Course at Dicoding Indonesia

## Domain Proyek

### Latar Belakang
Kesehatan Mental menurut seorang ahli kesehatan Merriam Webster merupakan suatu keadaan emosional dan psikologis yang baik dimana individu dapat memanfaatkan kemampuan kognisi, emosi, berfungsi dalam komunitasnya, dan memenuhi kebutuhan hidupnya sehari-hari [[1](http://eprints.undip.ac.id/38840/1/KESEHATAN_MENTAL.pdf#:~:text=Kesehatan%20mental%20menurut%20seorang%20ahli%20kesehatan%20Merriam%20Webster%2C,dalam%20komunitasnya%2C%20da%20n%20memenuhi%20kebutuhan%20hidupnya%20sehari-hari.)]. Kesehatan mental mempengaruhi kesejahteraan emosional, psikologis, dan sosial seseorang. Hal tersebut berpengaruh pada cara seseorang berpikir, merasakan, dan bertindak. Selain itu, kesehatan mental juga berpengaruh dalam membantu menentukan bagaimana seseorang menangani stres, interaksi dengan orang lain, dan menentukan pilihan.  

Salah satu faktor penting yang secara langsung maupun tidak langsung mempengaruhi kinerja maupun produktivitas karyawan, yaitu kesehatan mental. Hasil penelitian yang dilakukan oleh Koopman, dkk (2002) menyatakan bahwa produktivitas kerja dipengaruhi oleh kesehatan mental para pekerja [[2](https://www.jstor.org/stable/44995848)]. Dalam penelitiannya, Koopman, dkk. (2002) menemukan adanya hubungan yang sangat erat antara kedua variabel tersebut. Hal tersebut menunjukkan bahwa kesehatan mental mempunyai peran yang sangat penting dalam menciptakan ruang lingkup kerja yang efektif dan efisien. Oleh karena itu, salah satu cara yang dapat dilakukan guna menciptakan ruang lingkup kerja yang efektif dan efisien, yaitu dengan cara membangun model machine learning yang dapat digunakan untuk mengidentifikasi seorang karyawan yang membutuhkan perawatan kesehatan mental.

## Business Understanding

### Problem Statements
Berdasarkan latar belakang yang menjadi pembatas bahasan, adapun rincian masalah yang dapat diselesaikan pada proyek ini yang di antaranya adalah sebagai berikut:
* Dari serangkaian fitur yang ada, fitur apa yang paling berpengaruh terhadap kebutuhan seorang karyawan yang membutuhkan perawatan kesehatan mental?
* Apa model machine learning yang paling baik untuk memprediksi kebutuhan seorang karyawan yang membutuhkan perawatan kesehatan mental?

### Goals
Adapun tujuan dilakukannya proyek ini yang di antaranya adalah sebagai berikut:
* Membangun model machine learning yang dapat digunakan untuk memprediksi karyawan yang membutuhkan perawatan kesehatan mental.
* Membandingkan beberapa algoritma guna memperoleh akurasi terbaik dalam melakukan prediksi terhadap karyawan yang membutuhkan perawatan kesehatan mental.

### Solution Statements
Dalam rangka mencapai goals yang ada, penulis akan membangun model prediksi dengan 6 algoritma berbeda. Seluruh model tersebut nantinya akan dibandingkan guna mendapatkan model terbaik. Berikut merupakan algoritma yang penulis gunakan dalam membangun model prediksi:
* **Logistic Regression**  
Logistic Regression merupakan suatu cara permodelan masalah keterhubungan antara suatu variabel independen terhadap variabel dependen. Contohnya adalah menentukan apakah suatu nilai ukuran tumor tertentu termasuk kedalam tumor ganas atau tidak. [[6](https://vincentmichael089.medium.com/machine-learning-2-logistic-regression-96b3d4e7b603)]
* **K-Nearest Neighbors**  
K-Nearest Neighbors merupakan algoritma supervised
learning dimana hasil dari instance yang baru diklasifikasikan berdasarkan mayoritas dari kategori k-tetangga terdekat. [[7](https://medium.com/bee-solution-partners/cara-kerja-algoritma-k-nearest-neighbor-k-nn-389297de543e)]
* **Decision Tree**  
Decision Tree merupakan model prediksi menggunakan struktur pohon atau struktur berhirarki. [[8](https://medium.com/iykra/mengenal-decision-tree-dan-manfaatnya-b98cf3cf6a8d)]
* **Random Forest**  
Random Forest merupakan algoritma klasifikasi yang terdiri dari banyak Decision Tree. Algoritma ini menggunakan bagging dan feature randomness ketika membangun setiap pohon individu untuk mencoba membuat hutan pohon yang tidak berkorelasi yang prediksinya oleh komite lebih akurat daripada pohon individu mana pun. [[9](https://towardsdatascience.com/understanding-random-forest-58381e0602d2#:~:text=The%20random%20forest%20is%20a,that%20of%20any%20individual%20tree)]
* **Gradient Boosting**  
Gradient Boosting merupakan algoritma supervised learning dimana prediktor yang kuat dibangun dengan cara aditif atau berurutan menggunakan prediktor lemah, seperti Decision Tree. Algoritma ini biasa digunakan untuk tugas klasifikasi dan regresi. [[10](https://ankitnitjsr13.medium.com/gradient-boosting-algorithm-800e5b2bb3e4)]
* **AdaBoost**  
AdaBoost merupakan meta-algoritma klasifikasi statistik yang dirumuskan oleh Yoav Freund dan Robert Schapire pada tahun 1995, yang memenangkan Penghargaan Gödel 2003 untuk karya mereka. Algoritma ini dapat digunakan bersama dengan banyak jenis algoritma pembelajaran lainnya untuk meningkatkan kinerja. Output dari algoritma pembelajaran lainnya ('weak learners') digabungkan menjadi jumlah tertimbang yang mewakili output akhir dari pengklasifikasi yang ditingkatkan. [[11](https://en.m.wikipedia.org/wiki/AdaBoost)]
* **XGBoost**  
XGBoost yang merupakan singkatan dari Extreme Gradient Boosting merupakan library machine learning Gradient-Boosted Decision Tree (GDBT) terdistribusi yang dapat diskalakan dan didorong oleh gradien. Algoritma ini memberikan peningkatan pohon paralel dan merupakan perpustakaan pembelajaran mesin terkemuka untuk masalah regresi, klasifikasi, dan peringkat. [[12](https://www.nvidia.com/en-us/glossary/data-science/xgboost/#:~:text=XGBoost%2C%20which%20stands%20for%20Extreme,%2C%20classification%2C%20and%20ranking%20problems)]
