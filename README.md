# First-Project-Machine-Learning-Terapan
First Project of Machine Learning Terapan Course at Dicoding Indonesia

## Domain Proyek

Domain proyek yang diambil untuk proyek machine learning ini, yaitu **Kesehatan** dengan judul ***Predictive Analytics* : Prediksi Kebutuhan Perawatan Kesehatan Mental terhadap Seorang Karyawan**

### Latar Belakang

![Latar Belakang](/assets/FirstProject-MLT-LatarBelakang.png "Latar Belakang")

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
* Mencari fitur yang paling berpengaruh terhadap kebutuhan seorang karyawan yang membutuhkan perawatan kesehatan mental.

### Solution Statements
Dalam rangka mencapai goals yang ada, penulis akan membangun model prediksi dengan 6 algoritma berbeda. Seluruh model tersebut nantinya akan dibandingkan guna mendapatkan model terbaik. Berikut merupakan algoritma yang penulis gunakan dalam membangun model prediksi:
* **Logistic Regression**  
Logistic Regression merupakan suatu cara permodelan masalah keterhubungan antara suatu variabel independen terhadap variabel dependen. Contohnya adalah menentukan apakah suatu nilai ukuran tumor tertentu termasuk ke dalam tumor ganas atau tidak. [[6](https://vincentmichael089.medium.com/machine-learning-2-logistic-regression-96b3d4e7b603)]
* **K-Nearest Neighbors**  
K-Nearest Neighbors merupakan algoritma supervised
learning dimana hasil dari *instance* yang baru diklasifikasikan berdasarkan mayoritas dari kategori k-tetangga terdekat. [[7](https://medium.com/bee-solution-partners/cara-kerja-algoritma-k-nearest-neighbor-k-nn-389297de543e)]
* **Decision Tree**  
Decision Tree merupakan model prediksi menggunakan struktur pohon atau struktur berhirarki. [[8](https://medium.com/iykra/mengenal-decision-tree-dan-manfaatnya-b98cf3cf6a8d)]
* **Random Forest**  
Random Forest merupakan algoritma klasifikasi yang terdiri dari banyak Decision Tree. Algoritma ini menggunakan *bagging* dan *feature randomness* ketika membangun setiap pohon individu untuk mencoba membuat hutan pohon yang tidak berkorelasi yang prediksinya oleh komite lebih akurat daripada pohon individu mana pun. [[9](https://towardsdatascience.com/understanding-random-forest-58381e0602d2#:~:text=The%20random%20forest%20is%20a,that%20of%20any%20individual%20tree)]
* **Gradient Boosting**  
Gradient Boosting merupakan algoritma *supervised learning* dimana prediktor yang kuat dibangun dengan cara aditif atau berurutan menggunakan prediktor lemah, seperti Decision Tree. Algoritma ini biasa digunakan untuk tugas klasifikasi dan regresi. [[10](https://ankitnitjsr13.medium.com/gradient-boosting-algorithm-800e5b2bb3e4)]
* **AdaBoost**  
AdaBoost merupakan meta-algoritma klasifikasi statistik yang dirumuskan oleh Yoav Freund dan Robert Schapire pada tahun 1995, yang memenangkan Penghargaan Gödel 2003 untuk karya mereka. Algoritma ini dapat digunakan bersama dengan banyak jenis algoritma pembelajaran lainnya untuk meningkatkan kinerja. Output dari algoritma pembelajaran lainnya ('weak learners') digabungkan menjadi jumlah tertimbang yang mewakili *output* akhir dari pengklasifikasi yang ditingkatkan. [[11](https://en.m.wikipedia.org/wiki/AdaBoost)]
* **XGBoost**  
XGBoost yang merupakan singkatan dari Extreme Gradient Boosting merupakan library machine learning Gradient-Boosted Decision Tree (GDBT) terdistribusi yang dapat diskalakan dan didorong oleh gradien. Algoritma ini memberikan peningkatan pohon paralel dan merupakan perpustakaan pembelajaran mesin terkemuka untuk masalah regresi, klasifikasi, dan peringkat. [[12](https://www.nvidia.com/en-us/glossary/data-science/xgboost/#:~:text=XGBoost%2C%20which%20stands%20for%20Extreme,%2C%20classification%2C%20and%20ranking%20problems)]

## Dataset Understanding

![Dataset Understanding](/assets/FirstProject-MLT-DatasetUnderstanding.png "Dataset Understanding")

Dataset yang penulis gunakan dalam proyek ini, yaitu Dataset dengan judul Mental Health in Tech Survey yang diambil pada laman Kaggle [[3](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)]. Dataset tersebut berisikan 1259 data dengan  27 kolom. Berikut merupakan informasi lebih detail dari masing-masing kolom pada dataset:  
* `timestamp` : Catatan digital tentang waktu terjadinya peristiwa tertentu.
* `age` : Umur
* `gender` : Jenis Kelamin
* `country` : Negara
* `state` : Jika Anda tinggal di Amerika Serikat, di negara bagian atau wilayah mana Anda tinggal?
* `self_employed` : Apakah Anda wiraswasta?
* `family_history` : Apakah Anda memiliki riwayat keluarga penyakit mental?
* `treatment` : Sudahkah Anda mencari perawatan untuk kondisi kesehatan mental?
* `work_interfere` : Jika Anda memiliki kondisi kesehatan mental, apakah Anda merasa itu mengganggu pekerjaan Anda?
* `no_employees` : Berapa banyak karyawan yang dimiliki perusahaan atau organisasi Anda?
* `remote_work` : Apakah Anda bekerja dari jarak jauh (di luar kantor) setidaknya 50% dari waktu?
* `tech_company` : Apakah atasan Anda merupakan seseorang dari perusahaan / organisasi teknologi?
* `benefits` : Apakah atasan Anda memberikan manfaat kesehatan mental?
* `care_options` : Apakah Anda tahu pilihan untuk perawatan kesehatan mental yang diberikan atasan Anda?
* `wellness_program` : Apakah atasan Anda pernah membahas kesehatan mental sebagai bagian dari program kesehatan karyawan?
* `seek_help` : Apakah atasan Anda menyediakan sumber daya untuk mempelajari lebih lanjut tentang masalah kesehatan mental dan cara mencari bantuan?
* `anonymity` : Apakah anonimitas Anda dilindungi jika Anda memilih untuk memanfaatkan sumber daya perawatan kesehatan mental atau penyalahgunaan zat?
* `leave` : Seberapa mudah bagi Anda untuk mengambil cuti medis untuk kondisi kesehatan mental?
* `mentalhealthconsequence` : Apakah menurut Anda mendiskusikan masalah kesehatan mental dengan atasan Anda akan memiliki konsekuensi negatif?
* `physhealthconsequence` : Apakah menurut Anda mendiskusikan masalah kesehatan fisik dengan atasan Anda akan memiliki konsekuensi negatif?
* `coworkers` : Apakah Anda bersedia mendiskusikan masalah kesehatan mental dengan rekan kerja Anda?
* `supervisor` : Apakah Anda bersedia mendiskusikan masalah kesehatan mental dengan atasan langsung Anda?
* `mentalhealthinterview` : Apakah Anda akan mengemukakan masalah kesehatan mental dengan calon atasan dalam sebuah wawancara?
* `physhealthinterview` : Apakah Anda akan mengemukakan masalah kesehatan fisik dengan calon atasan dalam sebuah wawancara?
* `mentalvsphysical` : Apakah Anda merasa bahwa atasan Anda menganggap kesehatan mental seserius kesehatan fisik?
* `obs_consequence` : Pernahkah Anda mendengar atau mengamati konsekuensi negatif bagi rekan kerja dengan kondisi kesehatan mental di tempat kerja Anda?
* `comments` : Catatan atau komentar tambahan apa pun.

### Dataset Information
Kategori | Keterangan
--- | ---
Title | Mental Health in Tech Survey
Source | [Kaggle](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)
Maintainer | Open Sourcing Mental Illness, LTD.
License | CC BY-SA 4.0
Visibility | Public
Tags | Earth and Nature, Healthcare, Mental Health, Employment, and Genetics
Usability | 8.82

## Data Preparation

Teknik yang penulis gunakan pada tahap Data Preparation adalah sebagai berikut:
* **Encoding Feature Categorical**  
Pada tahap ini, penulis melakukan proses encoding terhadap fitur kategori dengan menggunakan teknik One-Hot-Encoding yang merupakan teknik untuk merepresentasikan variabel atau fitur kategorikan ke dalam vektor biner [[4]](https://medium.com/analytics-vidhya/one-hot-encoding-categorical-variables-what-is-it-why-is-it-how-is-it-6fd9ed3a161). Guna mewujudkan hal tersebut, penulis menggunakan teknik LabelEncoder pada library Scikitlearn.
* **Reduksi Dimensi dengan PCA (Principal Component Analysis)**  
Teknik reduksi (pengurangan) dimensi merupakan prosedur dimana jumlah fitur akan dikurangkan dengan tetap mempertahankan informasi pada data. Teknik ini penulis gunakan untuk mengurangkan jumlah fitur yang terdapat pada dataset. Dalam hal ini, penulis menggunakan Principal Component Analysis (PCA) sebagai teknik pengurangan dimensi. Teknik tersebut merupakan teknik yang digunakan untuk mereduksi dimensi, mengekstraksi fitur, dan mentransformasikan data dari “n-dimensional space” ke dalam sistem berkoordinat baru dengan dimensi m dimana m lebih kecil dari n [5].
* **Train-Test-Split**  
Pada tahap ini, penulis melakukan pembagian dataset menjadi data latih dan data uji menggunakan train_test_split dari library Scikitlearn. Pembagian dataset ini bertujuan agar nantinya dapat digunakan untuk melatih dan mengevaluasi kinerja model. Pada proyek ini, 80% dataset digunakan untuk melatih model, dan 20% sisanya digunakan untuk mengevaluasi model.
* **Standarisasi**  
Pada tahap ini, penulis menerapkan proses standarisasi guna menyamakan data pada skala yang relatif sama. Proses tersebut penulis lakukan agar algoritma machine learning menghasilkan performa yang lebih baik dan konvergen lebih cepat. Dalam hal ini, penulis menerapkan proses standarisasi pada fitur kategori dengan menggunakan teknik StandarScaler dari library Scikitlearn.

## Modeling

Pada tahap ini, penulis membangun model prediksi dengan menggunakan 7 algoritma berbeda, yaitu Logistic Regression, K-Nearest Neighbor, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, dan XGBoost. Metrik akurasi dari 7 algoritma tersebut kemudian penulis representasikan dengan menggunakan tabel dan diagram, seperti berikut:

### Accuracy Metric Information

Algoritma | Accuracy Score
-- | --
LogisticRegression | 0.515873
KNeighborsClassifier | 0.619048
DecisionTreeClassifier | 0.611111
RandomForestClassifier | 0.793651
GradientBoostingClassifier | 0.714286
AdaBoostClassifier | 0.507937
XGBClassifier | 0.761905

![Diagram Metrik Akurasi](/assets/FirstProject-MLT-AccuracyMetricDiagram.png "Diagram Metrik Akurasi")

Dengan demikian, berdasarkan diagram dan tabel di atas, dapat disimpulkan bahwa model prediksi yang dibangun dengan menggunakan algoritma Random Forest merupakan model dengan tingkat akurasi tertinggi dengan akurasi sebesar 0,79 atau 79%.

## Evaluation

Karena model merupakan model klasifikasi, model yang telah dibangun akan dievaluasi dengan menggunakan metode Confusion Matrix. Evaluasi dengan menggunakan confusion matrix ini akan menghasilkan nilai dari akurasi, presisi, recall, dan kappa untuk mengukur kesuksesan dari model prediksi dengan algoritma Random Forest yang merupakan model dengan tingkat akurasi tertinggi.  

Confusion matrix merupakan metode validasi data teks dari jumlah opini negatif dan positif yang tidak seimbang. Berikut merupakan ilustrasi dan penjelasan lebih detail dari confusion matrix:

![Confusion Matrix Explanation](/assets/FirstProject-MLT-ConfusionMatrixExplanation.png "Confusion Matrix Explanation")  

Berikut merupakan penjelasan dari masing-masing nilai yang terdapat pada confusion matrix:
* Nilai Prediksi adalah keluaran dari program dimana nilainya Positif dan Negatif.
* Nilai Aktual adalah nilai sebenarnya dimana nilainya True dan False.
* True Positive (TP) adalah keluaran program dimana nilainya Positif dan bersifat True.
* True Negative (TN) adalah keluaran program dimana nilainya Negatif dan bersifat True.
* False Positive (FP) adalah keluaran program dimana nilainya positif dan bersifat False.
* False Negative (FN) adalah keluaran program dimana nilainya Negatif dan bersifat False.  

Di samping itu, berikut merupakan ilustrasi dan penjelasan lebih detail dari nilai accuracy, recall, precision, dan kappa:

![Nilai Evaluasi](/assets/FirstProject-MLT-NilaiEvaluasi.png "Nilai Evaluasi")

Berikut merupakan penjelasan dari masing-masing nilai:
* Accuracy merupakan rasio antara prediksi yang benar dengan seluruh sampel yang diprediksi.
* Recall merupakan rasio antara prediksi positif yang benar dengan seluruh sampel positif (Actual).
* Precision merupakan rasio antara prediksi positif yang benar dengan seluruh prediksi positif (Prediction). 
* Kappa merupakan metrik yang membandingkan akurasi yang teramati dengan akurasi yang diharapkan.

Berikut merupakan confusion matrix yang didapat dari model prediksi menggunakan algoritma dengan tingkat akurasi terbaik, yaitu Random Forest:

![Confusion Matrix](/assets/FirstProject-MLT-ConfusionMatrix.png "Confusion Matrix")

Adapun nilai accuracy, precision, recall, dan kappa yang penulis representasikan pada tabel berikut:
Kategori | Evaluation Score
-- | --
Accuracy | 0.777778
Precision | 0.730769
Recall | 0.890625
Kappa | 0.553869

## Kesimpulan
Domain proyek yang diambil pada proyek machine learning ini, yaitu **Kesehatan** dengan judul ***Predictive Analytics* : Prediksi Kebutuhan Perawatan Kesehatan Mental terhadap Seorang Karyawan**. Proyek ini menggunakan 7 algoritma yang penulis bandingkan guna mendapatkan model terbaik. Model prediksi terbaik diperoleh dengan menggunakan algoritma Random Forest dengan tingkat akurasi sebesar 0.79 atau 79%. Terakhir, penulis melakukan evaluasi terhadap model tersebut dengan menggunakan confusion matrix. Evaluasi tersebut menghasilkan nilai accuracy sebesar 0.78 atau 78%, nilai precision sebesar 0,73 atay 73%, nilai recall sebesar 0.89 atau 89%, dan nilai kappa sebesar 0.55 atau 55%.

## Daftar Referensi
[[1](http://eprints.undip.ac.id/38840/1/KESEHATAN_MENTAL.pdf#:~:text=Kesehatan%20mental%20menurut%20seorang%20ahli%20kesehatan%20Merriam%20Webster%2C,dalam%20komunitasnya%2C%20da%20n%20memenuhi%20kebutuhan%20hidupnya%20sehari-hari.)] K. S. Dewi, Buku Ajar Kesehatan Mental, 2012, ISBN : 978-979-097-043-4, http://eprints.undip.ac.id/38840/1/KESEHATAN_MENTAL.pdf#:~:text=Kesehatan%20mental%20menurut%20seorang%20ahli%20kesehatan%20Merriam%20Webster%2C,dalam%20komunitasnya%2C%20da%20n%20memenuhi%20kebutuhan%20hidupnya%20sehari-hari.   

[[2](http://www.jstor.org/stable/44995848)] C. Koopman, K. R. Pelletier, J. F. Murray, C. E. Sharda, M. L. Berger, R. S. Turpin, P. Hackleman, P. Gibson, D. M. Holmes, and T. Bendel, "Stanford Presenteeism Scale: Health Status and Employee Productivity. Journal of Occupational and Environmental Medicine," Journal of Occupational and Environmental Medicine, vol. 44, no. 1, 14-20, 2002, http://www.jstor.org/stable/44995848.  

[[3](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)] O. Sourcing Mental Illness, LTD., "Mental Health in Tech Survey,"   Kaggle, 2014. https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey.   

[[4](https://medium.com/analytics-vidhya/one-hot-encoding-categorical-variables-what-is-it-why-is-it-how-is-it-6fd9ed3a161  )] Z. Luna., “One-Hot Encoding Categorical Variables — What is it? Why is it? How is it?,” Medium, 2021, https://medium.com/analytics-vidhya/one-hot-encoding-categorical-variables-what-is-it-why-is-it-how-is-it-6fd9ed3a161.  

[5] Machine Learning Terapan, Dicoding.

[[6](https://vincentmichael089.medium.com/machine-learning-2-logistic-regression-96b3d4e7b603)] V. Michael., "Machine Learning: Mengenal Logistic Regression," Medium, 2019, https://vincentmichael089.medium.com/machine-learning-2-logistic-regression-96b3d4e7b603.

[[7](https://medium.com/bee-solution-partners/cara-kerja-algoritma-k-nearest-neighbor-k-nn-389297de543e)] A. M. Ismail., "Cara Kerja Algoritma k-Nearest Neighbor (k-NN)," Medium, 2018, https://medium.com/bee-solution-partners/cara-kerja-algoritma-k-nearest-neighbor-k-nn-389297de543e. 

[[8](https://medium.com/iykra/mengenal-decision-tree-dan-manfaatnya-b98cf3cf6a8d)] IYKRA., "Mengenal Decision Tree dan Manfaatnya," Medium, 2018, https://medium.com/iykra/mengenal-decision-tree-dan-manfaatnya-b98cf3cf6a8d.  

[[9](https://towardsdatascience.com/understanding-random-forest-58381e0602d2#:~:text=The%20random%20forest%20is%20a,that%20of%20any%20individual%20tree)] T. Yiu., "Understanding Random Forest," Medium, 2019, https://towardsdatascience.com/understanding-random-forest-58381e0602d2#:~:text=The%20random%20forest%20is%20a,that%20of%20any%20individual%20tree.

[[10](https://ankitnitjsr13.medium.com/gradient-boosting-algorithm-800e5b2bb3e4)] MLMath.io., "Gradient Boosting Algorithm," Medium, 2019, https://ankitnitjsr13.medium.com/gradient-boosting-algorithm-800e5b2bb3e4.

[[11](https://en.m.wikipedia.org/wiki/AdaBoost)] "AdaBoost," Wikipedia, https://en.m.wikipedia.org/wiki/AdaBoost. 

[[12](https://www.nvidia.com/en-us/glossary/data-science/xgboost/#:~:text=XGBoost%2C%20which%20stands%20for%20Extreme,%2C%20classification%2C%20and%20ranking%20problems)] "XGBOOST," NVIDIA, https://www.nvidia.com/en-us/glossary/data-science/xgboost/#:~:text=XGBoost%2C%20which%20stands%20for%20Extreme,%2C%20classification%2C%20and%20ranking%20problems. 
