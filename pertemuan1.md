## Pertemuan 1: Pengenalan Algoritma
## Tujuan pembelajaran
 1. Memahami konsep dasar algoritma
 2. Mengetahui karakteristik algoritma yg baik.
 3. Mengenal notasi algoritma.
 4. Mampu memahami contoh algoritma sederhana.

## 1. Apa itu Algoritma?
 - Algoritma adalah langkah-langkah sistematis yg digunakan untuk menyelesaikan suatu masalah
 - Contoh Sederhana algoritma dalam kehidupan sehari-hari
    - Membuat mie instan:
     1. Rebus air hingga mendidih.
     2. Masukan mie ke dalam air mendidih.
     3. Tunggu beberapa menit hingga mie matang.
     4. Tiriskan mie dan campurkan dengan bumbu.
     5. Mie siap disajikan.

## Ciri-ciri algoritma:
 - Jelas dan terstruktur : Setiap langkah harus mudah dipahami
 - Harus mimiliki titik dan awal dan akhir : Tidak boleh loop tanpa henti
 - Harus menghasilkan output yg sesuai : Output harus sesua dengan masalah yg diselesaikan
 - dapat dieksekusi dalam waktu terbatas: Tidak boleh membutuhkan waktu tak terbatas

## 2. Karakteristik Algoritma yg baik
## Agar algoritma dapat digunakan dengan efektif, harus memiliki beberapa karakteristik berikut:
 1. Finiteness(Terbatas)
    - Algoritma harus memiliki langkah-langkah yg terbatas, tidak boleh berjalan tanpa henti.
 2. Definiteness(Pasti&jelas)
    - Setiap langkah harus jelas dan tidak ambigu
 3. Input dan Output
    - Harus ada input (data awal) dan menghasilkan output (hasil)
 4. Effectiveness (Efektif & efisien)
    - Setiap langkah dapat dijalankan dengan mudah oleh manusia atau komputer.\
 5. Generality (Bersifat umum)
    - Algoritma harus bisa diterapkan untuk berbagai kasus yg serupa.

## 3. Notasi Algoritmik
## Notasi algoritmik adalah cara untuk menulis algoritma secara normal. Ada beberapa metode yg umum digunakan:
*a. Notasi Deskriptif (Bahasa Natural)*
 - Menulis algoritma dengan bahasa manusia secara jelas
 - Contoh: Algoritma Menukar Dua angka
    - Langkah 1: Masukan nilai A dan B
    - Langkah 2: Simpan nilai B ke A
    - Langkah 3: Pindahkan nilai B ke A
    - Langkah 4: Pindahkan nilai T ke B
    - Langkah 5: Cetak hasil A dan B
*b. Notasi Pseudocode*
 - Cara menuliskan algoritma menyerupai bahasa pemrograman
 - Contoh:
 """
 Mulai
    Baca A, B
    T = A
    A = B
    B = T
    Tampilkan A, B
Selesai
 """

*c. Notasi Flowchart*
 - Flowchart adalah diagram visual yg menggambarkan algoritma dengan simbol-simbol standar.
 - Contoh flowchart untuk menukar dua angka:
 ```r
 Mulai Baca A, B > Simpan A ke T > A = B > B = T > Cetak A, B Selesai
 ```

## 4. Contoh Algoritma Sederhana
# Contoh 1: Menentukan Bilangan Ganjil atau Genap
**Deskripsi Algoritma:**
 1. Masukan bilangan N.
 2. Jika N mod 2 = 0, Maka N adalah bilangan genap.
 3. Jika tidak, maka N adalah bilangan ganjil.
 4. Tampilkan hasilna.

*Pseudocode*

```plaint
Mulai
    Baca N
    Jika N mod 2 = 0 Maka
        Cetak "N adalah bilangan genap"
    Jika Tidak Maka
        Cetak "N adalah bilangan ganjil"
Selesai
```
*Contoh menukar dua bilangan*
```
Mulai
    Baca A, B
    T = A
    A = B
    B = T
    Cetak A, B
Selesai
```

## Kesimpulan
 1. Algoritma adalah langkah-langkah sestematis untuk menyelesaiakan masalah.
 2. Karakteristik algoritma yg baik: harus jelas, terbatas, memiliki input-output, efektif, dan bersifat umum
 3. Notasi algoritmik: dapat ditulis dalam bentuk deskriptif, pseudocode, atau flowchart.
 4. Contoh algoritma sederhana: menentukan ganjil/genap dan menukar dua angka
