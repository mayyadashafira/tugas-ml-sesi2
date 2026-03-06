# Tugas Machine Learning Sesi 2 - Titanic Dataset

**Deskripsi**
Repository ini berisi hasil praktik manipulasi dan pembersihan data (Data Preprocessing) menggunakan Python dan dataset Titanic. Langkah-langkah ini dilakukan sebagai persiapan sebelum data dimasukkan ke dalam model Machine Learning.

## Apa yang Dipelajari?
Saya mempelajari dan mempraktikkan alur kerja pemrosesan data, yang meliputi:
* Data Loading : Membaca dataset dari URL Github dengan mengguanakan pandas.
* Eksplorasi Data Awal (EDA) : Melihat struktur data dengan shape dan head, serta mengecek adanya missing values pada setiap kolom.
* Data Cleaning : Menghapus kolom yang tidak relevan (PassengerId, Name, Ticket, Cabin), mengisi nilai umur (Age) yang kosong dengan median, dan menghapus baris yang masih memiliki data kosong.
* Feature Engineering : Mengubah data kategorikal seperti Sex dan Embarked menjadi data numerik menggunakan one-hot encoding.
* Normalisasi Data (Scaling) : Menggunakan MinMaxScaler untuk menyesuaikan skala data ke rentang 0–1 agar model Machine Learning tidak bias terhadap nilai yang lebih besar.


## Langkah-langkah Upload (Push) File ke Repository GitHub
**Langkah-langkah Upload ke GitHub:**
* Melakukan inisialisasi lokal dengan `git init`.
* Menambahkan file ke area staging dengan `git add .`
* Menyimpan perubahan dengan `git commit -m "pesan commit"`.
* Menghubungkan folder ke repository GitHub dengan `git remote add origin https://github.com/mayyadashafira/tugas-ml-sesi2`
* Menarik pembaruan dari GitHub (jika ada file yang bentrok) dengan `git pull origin main`.
* Mengunggah file ke GitHub dengan `git push -u origin main`.
