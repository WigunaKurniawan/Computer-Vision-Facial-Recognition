# Computer-Vision-Facial-Recognition
Building Computer Vision: Facial Recognition Using FaceNet based Neural Network

## Latar Belakang
Face Recognition merupakan masalah computer vision untuk mendeteksi dan mengidentifikasi wajah manusia didalam sebuah gambar atau video. Prosesnya dimulai dengan mendeteksi dan melokasikan posisi waja pada gambar yang dimasukkan untuk diproses. Setelah terdeteksi, sebuah feature set yang disebut facial footprint atau face embedding, dibuat dari berbagai key point pada awaja. Wajah manusia memiliki 80 nodal points yang digunakan untuk membuat feature set. Kemudain feature set tersebut kemduian dibandingkan dengan database untuk membangun identitas wajah manusia tersebut. Ada beberapa aplikasi facial recognition didalam kehidupan nyata seperti:
1. Sebagai password untuk mengakses kontrol pada area dengan keamanan tingkat tinggi
2. Beacukai dan perbatasan wilayah
3. Mengidentifikasi genetic disorder
4. Memprediksi umur dan gender dari individual
5. Law enforcement
6. Mengorganisasikan album digital foot, dll.

Dalam portfolio ini, developer ingin mengeksplor FaceNet, sebuah algoritma face recognition yang dikembangkan oleh Google Engineers. Developer ingin mempelajari bagaimana FaceNet mengembangkan model face recognition. Terakhir, developer menulis kode untuk mengembangkan fungsi sistem face recognition secara lengkap yang bisa mendeteksi wajah secara real-time dari video live streaming.

## FaceNet
Algoritma Deep Neural Network ini ditemukan oleh tiga Google Engineers yakni Florian Schoff, Dmitry Kalenichneko dan James Philbin. Mereka mempublikasikan penelitian mereka pdaa tahun 2015 dalam sebuah papaer yang berjudul " FaceNet: A Unified Embedding for Face Recognition adn Clustering" ( https://arxiv.org/pdf/1503.03832.pdf ). FaceNet merupakan Unified System yang menyediakan kemampuan berikut ini:
1. Face Recognition ( Apakah ini orang yang sama?)
2. Recognition ( Siapa orang ini? )
3. Clustering ( Apa orang ini mirip? )

FaceNet merupakan Deep Neural Network yang melakukan berbagai hal sebagai berikut:
1. Mengkomputasi sebauh 128D feature vector, yang disebut face embedding, dari gambar yang di inputkan. Disini, 128D feature vector merupakah suatu list dari 128 real-valued numbers, yang memrepresentasikan output yang berskala mengkuantifikasi wajah
2. Mempelajari dengan mengoptimalkan suatu triplet loss function.


![image](https://user-images.githubusercontent.com/32436655/141946928-cf06587d-d963-4170-9a8c-cb886089523a.png)
FaceNet Neural Network Architecture
