# Analisis Komparatif Logistic Regression dan Decision Tree Untuk Memprediksi Keselamatan Penumpang Kapal RMS Titanic
#### Proyek Akhir Mata Kuliah Pengantar Data Sains
#### Disusun oleh: Siti Fadilah Nurkhotimah 
---
## Deskripsi Proyek
Proyek ini membandingkan algoritma Logistic Regression dan Decision Tree untuk mengidentifikasi pola signifikan pada karakteristik penumpang berdasarkan metrik evaluasi kinerja model. Penelitian ini bertujuan memberikan prediksi yang logis dan objektif pada data baru melalui perbandingan performa serta stabilitas model menggunakan uji K-Fold Cross Validation.

## Deskripsi Fitur Dataset
- Survived = Status keselamatan (0 = Tidak Selamat, 1 = Selamat)
Tipe data: Biner (Target Varibel)
- Pclass = Kelas penumpang (1, 2, 3)
Tipe data: Kategorik
- Sex = Jenis kelamin penumpang
Tipe data: Kategorik
- Age = Usia penumpang
Tipe data: Numerik
- SibSp = Jumlah saudara kandung atau pasangan di kapal Titanic
Tipe data: Numerik
- Fare = Harga tiket penumpang
Tipe data: Numerik
- PassengerId = Identitas (ID) penumpang
Tipe data: Integer (Identitas)
- Name = Nama penumpang
Tipe data: Object (Identitas)
- Ticket = Nomor tiket
Tipe data: Kategorik (Identitas)
- Cabin = Nomor cabin
Tipe data: Kategorik
- Parch = Jumlah orang tua atau anak di kapal Titanic
Tipe data: Numerik
- Embarked = Pelabuhan keberangkatan (C = Cherbourg; Q = Queenstown; S = Southampton)
Tipe data: Kategorik

## Struktur Data
- data_titanic.xlsx: Dataset historis yang digunakan sebagai data latih untuk membangun dan melatih model Logistic Regression dan Decision Tree.
- data_prediksi.xlsx: Dataset independen (418 penumpang) yang digunakan sebagai data uji untuk mengevaluasi kemampuan generalisasi model terhadap data baru.
- hasil_prediksi.xlsx: Output akhir yang berisi label prediksi keselamatan (0 atau 1) yang dihasilkan oleh model terbaik untuk kebutuhan analisis lebih lanjut.


_© 2025 Siti Fadilah Nurkhotimah. All rights reserved. Dokumen ini disusun untuk kepentingan portofolio akademik._
