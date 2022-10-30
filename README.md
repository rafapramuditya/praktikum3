Latihan 1
Penggunaan end
Parameter akhir dalam fungsi cetak digunakan untuk menambahkan string apa pun. Di akhir output dari pernyataan print dengan python. Secara default, fungsi cetak diakhiri dengan baris baru. Melewati spasi putih ke parameter akhir (end=' ') menunjukkan bahwa karakter akhir harus diidentifikasi oleh spasi putih dan bukan baris baru.

print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
![Gambar1](gambar/gambar1.png)

Penggunaan Seperator

w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
![Gambar1](gambar/gambar2.png)

String Format

String Formatting atau Pemformatan string memungkinkan kita menyuntikkan item ke dalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.

# string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
![Gambar1](gambar/gambar5.png)

String Format 2

print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(0, 10**1))
print('{0:>3} {1:>16}'.format(0, 10**2))
print('{0:>3} {1:>16}'.format(0, 10**3))
print('{0:>3} {1:>16}'.format(0, 10**4))
print('{0:>3} {1:>16}'.format(0, 10**5))
print('{0:>3} {1:>16}'.format(0, 10**6))
print('{0:>3} {1:>16}'.format(0, 10**7))
print('{0:>3} {1:>16}'.format(0, 10**8))
print('{0:>3} {1:>16}'.format(0, 10**9))
print('{0:>3} {1:>16}'.format(0, 10**10))
![Gambar1](gambar/gambar6.png)

Hasil Latihan 1

![Gambar1](gambar/gambar7.png)


Latihan 2

Input Variable
Penggunaan python untuk menginput nilai variabel dengan cara

a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
![Gambar1](gambar/gambar8.png)

Cetak Variable
Mencetak nilai kedua variabel ketika sudah di input

print("variable a=",a)
print("variable b=",b)
![Gambar1](gambar/gambar9.png)

Penggabungan Variable
Penggabungan kedua nilai Variable

print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
![Gambar1](gambar/gambar10.png)

Input Variable 2
Penggunaan python untuk menginput kedua variable

a=int(a)
b=int(b)
![Gambar1](gambar/gambar11.png)

Konversi Nilai Variable
Mencetak kembali hasil mengkonversi nilai kedua variabel

print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}+{0}=%d".format(a,b) %(a/b))
![Gambar1](gambar/gambar12.png)

Hasil Latihan 2

Latihan 3 Menggunakan String Format untuk membuat Belah Ketupat
![Gambar1](gambar/gambar13.png)

Latihan 4 Luas Lingkaran
Flowchart untuk mencari Luas dan keliling Lingkaran
![Gambar1](gambar/gambar14.png)

praktikum 3
![Gambar1](gambar/gambar15.png)

hasil praktikum 3 yang telah saya lakukan yaitu:

- dapat memehami algoritma lingkaran yang diprotes dalam python
- dapat menjalankan bagaimana langkah-langkah membuat algoritma lingkaran pada python
- dapat mebuat flowchart algoritma dengan baik dan benar
- dapat mengoperasikan langsung algoritma lingkaran pada python
