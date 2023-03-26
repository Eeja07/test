# Programming Assignment 2: Object Oriented Programming

Dalam programming assignment kali ini, Anda diminta untuk membuat program SIM Akademik sederhana dengan menggunakan paradigma OOP.
Class yang harus Anda buat adalah class yang sesuai dengan yang telah Anda buat pada tugas sebelumnya.
Sebagai template awal Anda akan diberikan contoh penggunaan include dengan menggunakan custom hpp file.

## Langkah-langkah yang perlu dilakukan

1. Buat hpp file pada folder src/include sesuai dengan nama class yang akan Anda buat.
2. Deklarasikan seluruh class (attribute dan method) sesuai dengan desain yang telah Anda buat pada tugas sebelumnya.
3. Buat file cpp pada folder src untuk mendefinisikan seluruh method yang belum diimplementasikan sesuai dengan deklarasi yang ada pada file hpp yang telah dibuat.
4. Buatlah operasi sederhana pada fungsi main() untuk mengoperasikan class-class yang telah didefinisikan.
5. Jika Anda menggunakan namespace custom maka akan ada tambahan nilai.

# Laporan Programming Assignment 2: Object Oriented Programming
## Source Code hpp :
![Screen Shot 2023-03-25 at 15 00 39](https://user-images.githubusercontent.com/115524218/227705524-fbe26d14-d3f0-49e4-ad53-1c5e210c937c.png)
## Source Code cpp :
![Screen Shot 2023-03-25 at 15 01 54](https://user-images.githubusercontent.com/115524218/227705575-eb9c761b-5dff-4439-8643-82091e34ae69.png)

![Screen Shot 2023-03-25 at 15 02 25](https://user-images.githubusercontent.com/115524218/227705579-dc5b75f9-6d48-45a1-b31b-0b275ec09fc3.png)

![Screen Shot 2023-03-25 at 15 02 50](https://user-images.githubusercontent.com/115524218/227705584-1a246f98-1d4f-4400-91c8-66e89711f7ec.png)

## Output Code :
![Screen Shot 2023-03-25 at 15 05 54](https://user-images.githubusercontent.com/115524218/227705587-28912d5a-16d5-4058-ab83-e40347e56061.png)

## Penjelasan :
1. Untuk source code hpp terdapat 5 File hpp sesuai dengan class yang ingin saya buat yaitu ada Mahasiswa.hpp, Kuesioner.hpp, FRS.hpp, Nilai.hpp, Dan Jadwal_Kuliah.hpp
2. Pada setiap file hpp memiliki kerangka yang sama dimana pada line 1 dan 2 terdapat #ifndef dan #define dimana dua kode ini berfungsi untuk menghindari duplikasi definisi dalam suatu berkas header atau suatu file sumber yang di-include beberapa kali. Pada line 4 dan 5 yaitu #include iostream dan string merupakan file header yang berisi definisi standar pada c++. Pada line 7 untuk "using namespace std;" merupakan perintah untuk mengimpor seluruh namespace 'std' ke dalam program sehingga tidak perlu menambakan prefix 'std::'. Pada line line selanjutnya pada tiap file hpp terdapat namespace costum dan class, dimana untuk classnya terdiri definisi dari atribut masing-masing dan juga untuk semua classnya terdapat "public:" yang berarti aksesibilitas class tersebut bersifat publik sehingga atribut-atribut data yang didefinisikan di dalamnya dapat diakses dari luar class. Pada line terakhir fungsi dari kode #endif untuk mengakhiri kode yang dimulai dengan #ifndef.
3. Untuk file main.cpp pada line 1 dan 2 diawali dengan #include iostream dan string yang merupakan file header yang berisi definisi standar pada c++. Pada line 4-8 Terdapat kode #include "hpp" yang dimana kode ini berfungsi untuk mempersingkat kode yang ada di main.cpp dikarenakan header file yang kita include berisi kode untuk class class yang kita buat. Pada line 10 untuk "using namespace std;" merupakan perintah untuk mengimpor seluruh namespace 'std' ke dalam program sehingga tidak perlu menambakan prefix 'std::'. Pada line 12-130 merupakan fungsi utama yang didalamnya terdapat operasi sederhana yaitu mendefinisikan nilai dari atribut atribut yang sudah dideklarasi kemudian ditampilkan dalam bentuk output ke layar menggunakan perintah 'cout'. Pada line 14 yang berisi "Mahasiswa::Mahasiswa Mahasiswa;" dimana "Mahasiswa::" adalah sintaks yang digunakan untuk menunjukkan bahwa Mahasiswa adalah bagian dari namespace Mahasiswa sedangkan "Mahasiswa Mahasiswa;" adalah deklarasi variabel yang menginisialisasi objek dari class Mahasiswa. Hal ini berlaku juga pada line 38, 56, 84, dan 108.
