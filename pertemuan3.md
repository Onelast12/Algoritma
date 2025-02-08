## 📚 Pertemuan 3: Pseudocode dan Flowchart
# 🎯 Tujuan Pembelajaran:
*Pada pertemuan ini, kita akan mempelajari:*
 1. Apa itu Pseudocode dan Flowchart?
 2. Penulisan Pseudocode
 3. Simbol-Simbol Flowchart
 4. Contoh Pseudocode dan Flowchart dalam Pemrograman
 5. Latihan Membuat Pseudocode dan Flowchart
* Setelah memahami materi ini, kalian akan mampu membuat representasi algoritma dalam bentuk pseudocode dan flowchart sehingga lebih mudah untuk diimplementasikan dalam kode program. 🚀

# 1️⃣ Apa itu Pseudocode dan Flowchart?
# 📝 Pseudocode
* Pseudocode adalah penulisan algoritma dalam bentuk teks sederhana yang menyerupai bahasa pemrograman.
* Tidak memiliki aturan sintaks yang ketat seperti bahasa pemrograman asli.
* Tujuannya untuk membantu memahami alur logika sebelum menuliskannya dalam kode.
📌 Contoh Pseudocode Sederhana:
*plaintext*
```
Mulai
    Baca nilai A dan B
    C = A + B
    Cetak C
Selesai
```
📌 Terjemahan dalam Python:
*python*
```
A = int(input("Masukkan nilai A: "))
B = int(input("Masukkan nilai B: "))
C = A + B
print("Hasil penjumlahan:", C)
```
# 🔄 Flowchart
* Flowchart adalah diagram grafis yang menggambarkan alur algoritma menggunakan simbol-simbol standar.
* Lebih mudah dipahami dibandingkan hanya membaca teks.
📌 Contoh Flowchart Sederhana (Menjumlahkan Dua Bilangan):
```
🔽 Mulai
➡ Masukkan A, B
➡ C = A + B
➡ Tampilkan C
🔼 Selesai
```
2️⃣ Penulisan Pseudocode
Pseudocode menggunakan struktur berikut:
* Input → Memasukkan data (misalnya: "Baca angka").
* Proses → Melakukan operasi (misalnya: "Hitung jumlah").
* Output → Menampilkan hasil (misalnya: "Cetak hasil").
📌 Contoh Pseudocode untuk Menentukan Bilangan Genap atau Ganjil:
plaintext
```
Mulai
    Baca bilangan N
    Jika N mod 2 = 0 Maka
        Cetak "Bilangan Genap"
    Jika Tidak Maka
        Cetak "Bilangan Ganjil"
Selesai
```
📌 Terjemahan dalam Python:
*python*
```
N = int(input("Masukkan bilangan: "))
if N % 2 == 0:
    print("Bilangan Genap")
else:
    print("Bilangan Ganjil")
```
# 3️⃣ Simbol-Simbol Flowchart
# Flowchart menggunakan simbol standar:

*Simbol	Fungsi	Gambar*
Terminator	Menunjukkan "Mulai" atau "Selesai"	🔽 / 🔼
Paralelogram	Input/Output (misalnya: "Baca" atau "Cetak")	⬛
Persegi Panjang	Proses (misalnya: "Hitung jumlah")	▭
Belah Ketupat	Keputusan (misalnya: "Jika kondisi X terpenuhi")	◇
Panah	Arah alur algoritma	➡
4️⃣ Contoh Pseudocode dan Flowchart dalam Pemrograman
📌 Contoh 1: Menentukan Apakah Angka Positif, Negatif, atau Nol

*Pseudocode:*
plaintext
```
Mulai
    Baca angka N
    Jika N > 0 Maka
        Cetak "Angka Positif"
    Jika N < 0 Maka
        Cetak "Angka Negatif"
    Jika Tidak Maka
        Cetak "Angka Nol"
Selesa
```
*Flowchart:*
```
🔽 Mulai
➡ Masukkan N
➡ N > 0?
✅ Ya ➡ Cetak "Angka Positif"
❌ Tidak ➡ N < 0?
✅ Ya ➡ Cetak "Angka Negatif"
❌ Tidak ➡ Cetak "Angka Nol"
🔼 Selesai
📌 Kode dalam Python:
```
*python*
```
N = int(input("Masukkan bilangan: "))
if N > 0:
    print("Angka Positif")
elif N < 0:
    print("Angka Negatif")
else:
    print("Angka Nol")
```

# 5️⃣ Latihan Membuat Pseudocode dan Flowchart
# 💡 Tugas: Buat pseudocode dan flowchart untuk:

 1. Menentukan apakah seseorang lulus atau tidak dengan syarat nilai ≥ 70.
 2. Menghitung luas persegi panjang (panjang × lebar).
# 📌 Petunjuk:
* Gunakan struktur IF untuk soal pertama.
* Gunakan operasi aritmatika sederhana untuk soal kedua.
# 📌 Kesimpulan Pertemuan 3
* ✅ Pseudocode digunakan untuk menulis algoritma dalam bentuk teks sederhana.
* ✅ Flowchart digunakan untuk menggambarkan algoritma dengan diagram.*
* ✅ Keduanya membantu memahami alur logika sebelum mengubahnya menjadi kode program.