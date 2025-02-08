## 📚 Pertemuan 2: Struktur Dasar Algoritma
## 🎯 Tujuan Pembelajaran:
*Hari ini kita akan belajar tentang struktur dasar algoritma yang terdiri dari:*

 1. Algoritma Sekuensial (Urutan)
 2. Algoritma Percabangan (Pemilihan)
 3. Algoritma Perulangan (Pengulangan)
 4. Contoh Kasus dan Latihan
*Setelah memahami materi ini, kalian akan bisa membuat algoritma sederhana yang bisa digunakan dalam pemrograman! 🚀*

## 1️⃣ Algoritma Sekuensial (Urutan)
* 💡 Apa itu algoritma sekuensial?*
*Algoritma yang dieksekusi berurutan dari langkah awal hingga akhir, tanpa percabangan atau pengulangan.*
*Cocok untuk tugas sederhana yang hanya membutuhkan urutan langkah tetap.*
*📌 Contoh Algoritma:*
*Membuat teh manis panas*

 1. Panaskan air hingga mendidih.
 2. Masukkan teh celup ke dalam gelas.
 3. Tuangkan air panas ke dalam gelas.
 4. Tambahkan gula sesuai selera.
 5. Aduk hingga gula larut.
 6. Teh manis siap disajikan!
## ✏ Pseudocode-nya:

*plaintext*
```
Mulai
    Panaskan air
    Masukkan teh celup ke gelas
    Tuangkan air panas
    Tambahkan gula
    Aduk rata
    Sajikan teh
Selesai
```
## 📌 Contoh dalam kode Python:
*python*
```
print("Panaskan air")
print("Masukkan teh celup ke gelas")
print("Tuangkan air panas")
print("Tambahkan gula")
print("Aduk rata")
print("Teh siap disajikan!")
```
👉 Kesimpulan:
Sekuensial = dikerjakan berurutan tanpa pilihan atau perulangan.
Berguna untuk proses yang tidak memerlukan kondisi khusus.

# 2️⃣ Algoritma Percabangan (Pemilihan)
# 💡 Apa itu algoritma percabangan?

 - Algoritma yang menggunakan kondisi untuk menentukan jalur eksekusi program.
 - Jika kondisi terpenuhi, lakukan tindakan A. Jika tidak, lakukan tindakan B.
*📌 Contoh Algoritma:*
*Menentukan bilangan ganjil atau genap*
 1. Masukkan bilangan N.
 2. Jika N habis dibagi 2, maka bilangan genap.
 3. Jika tidak, maka bilangan ganjil.
 4. Tampilkan hasilnya.

*✏ Pseudocode-nya:*

*plaintext*
```
Mulai
    Baca N
    Jika N mod 2 = 0 Maka
        Cetak "N adalah bilangan genap"
    Jika Tidak Maka
        Cetak "N adalah bilangan ganjil"
Selesai
```
📌 Contoh dalam kode Python:
*python*
```
N = int(input("Masukkan bilangan: "))
if N % 2 == 0:
    print("N adalah bilangan genap")
else:
    print("N adalah bilangan ganjil")
```
## 👉 Kesimpulan:
 1. Percabangan digunakan untuk pengambilan keputusan dalam algoritma.
 2. Digunakan saat kita ingin program berjalan dengan kondisi tertentu.

## 3️⃣ Algoritma Perulangan (Looping)
* 💡 Apa itu algoritma perulangan?
*Algoritma yang memungkinkan suatu proses diulang beberapa kali berdasarkan kondisi tertentu.*
*Digunakan jika ada tugas yang harus dilakukan berkali-kali.*
*📌 Contoh Algoritma:*
*Menampilkan angka 1 sampai 5*
```
Mulai dari angka 1.
Cetak angka.
Tambah angka dengan 1.
Ulangi langkah 2 dan 3 hingga angka mencapai 5.
✏ Pseudocode-nya:
```
plaintext
```
Mulai
    Set i = 1
    Selama i <= 5, lakukan:
        Cetak i
        Tambah i + 1
Selesai
```
📌 Contoh dalam kode Python (menggunakan while loop):
python
```
i = 1
while i <= 5:
    print(i)
    i += 1
```
📌 Contoh dalam kode Python (menggunakan for loop):
python
```
for i in range(1, 6):
    print(i)
```
## 👉 Kesimpulan:
 1. Looping digunakan untuk mengulang tugas yang sama tanpa menulis kode berulang.
 2. Memudahkan proses otomatisasi dalam pemrograman.
## 4️⃣ Contoh Kasus: Menghitung Diskon Belanja
* Seorang pelanggan mendapat diskon 10% jika total belanja lebih dari Rp100.000. Jika kurang dari itu, tidak ada diskon.

✏ Pseudocode-nya:
plaintext
```
Mulai
    Baca total_belanja
    Jika total_belanja > 100000 Maka
        diskon = total_belanja * 10 / 100
    Jika Tidak Maka
        diskon = 0
    total_bayar = total_belanja - diskon
    Cetak total_bayar
Selesai
```
# 📌 Contoh dalam kode Python:

*python*
```
total_belanja = int(input("Masukkan total belanja: "))
if total_belanja > 100000:
    diskon = total_belanja * 10 / 100
else:
    diskon = 0
total_bayar = total_belanja - diskon
print(f"Total yang harus dibayar: Rp{total_bayar}")
```

# 📌 Kesimpulan Pertemuan 2
* ✅ Algoritma Sekuensial → Langkah berurutan tanpa percabangan atau perulangan.
* ✅ Algoritma Percabangan → Memilih langkah berdasarkan kondisi (if-else).
* ✅ Algoritma Perulangan → Mengulang proses menggunakan loop.
* ✅ Penggunaan algoritma ini mempermudah pemrograman dan menyelesaikan masalah secara efisien.

# 📖 Tugas untuk Pertemuan Selanjutnya
# Buat algoritma (deskriptif dan pseudocode) untuk menghitung luas lingkaran!
```
Input: Jari-jari
Proses: Luas = π * r²
Output: Luas lingkaran
```
# Coba buat flowchart untuk menentukan apakah seseorang berhak mendapat diskon berdasarkan total belanja!
# 💡 Diskusi di kelas:
* Kapan kita lebih baik menggunakan percabangan daripada perulangan?
* Bagaimana cara meminimalkan kesalahan dalam menulis algoritma?
