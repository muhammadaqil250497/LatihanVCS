# LatihanVCS

# Tugas pertemuan ke 4, 5 Dan 6 Bahasa Pemrograman

Nama : M. Aqil Alfarid

NIM : 312010140

Kelas : TI.20.B.1

Prodi : Teknik Informatika




# Cara Menggunakan Git dan Github :


1. Install git terlebih dahulu (www.git-scm.com)

2. Setelah Menginstall Git, silahkan cek untuk melihat versi Git yg anda install dengan mengetik di CMD " git version "

3. Selanjutnya , masukkan username GitHub anda menggunakan perintah dibawah ini, Lalu tekan ENTER jika sudah benar.

![Gambar](screenshot-git/Screenshot1.png)

4. Kemudian masukkan email yang terdafrtar di GitHub anda menggunakan perintah dibawah ini, lalu tekan ENTER jika sudah benar.

![Gambar](screenshot-git/Screenshot2.png)

5. Selanjutnya untuk memastikan proses login Anda berhasil, maka lakukan perintah berikut.

![Gambar](screenshot-git/Screenshot3.png)

6. Login ke Github

![Gambar](screenshot-git/Screenshot8.png)

7. Buat akun terlebih dahulu jika anda baru pertama kali menggunakan GitHub (www.github.com)

8. Buat Repository baru dengan pilihan "New Repository" pada Home GitHub.

9. Jika sudah buat folder "LatihanVCS" dan buatlah file contoh "README.md"

10. Jika sudah Buka GitBash lalu masukkan perintah berikut.

![Gambar](screenshot-git/Screenshot4.png)

11. Selanjutnya , Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap Kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan.
Masukkan perintah berikut untuk membuat commit.

![Gambar](screenshot-git/Screenshot5.png)

12. Setelah git commit, lalu anda masukkan perintah git log . Untuk melihat status Kontributor apa aja yang update.

![Gambar](screenshot-git/Screenshot6.png)

13. Lakukan Remote Repository berfungsi untuk mengupload file yang telah anda buat sebelumnya di Local Disk. Masukkan perintah berikut ini untuk melakukan Remote Repository.

![Gambar](screenshot-git/Screenshot7.png)

14. Langkah Terakhir adalah Push ke Github. Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub. " git push -u origin "
--> Perintah di Atas akan menampilkan Pop Up Sign In Github. Anda perlu login untuk melanjutkan proses Push ke Github.

15. Selesai Anda sudah berhasil menginstall Git dan juga menggunakan Git dan GitHub.

![Gambar](screenshot-git/Screenshot9.png)



# PYHTON


# Tugas pertemuan ke 5

![Gambar](screenshot-pyhton/py0.png)

1. Saat ini saya akan menjelaskan hasil dari tugas tersebut berikut source code nya:

![Gambar](screenshot-pyhton/py1.png)

Source code diatas berfungsi untuk mencetak hasil / output berupa "====Biodata====".

untuk menampilkan output, saya menggunakan tanda petik dua didalam fungsi print("")

![Gambar](screenshot-pyhton/py4.png)


2. Untuk menghitung rumus umur saya menggunakan variable dob yaitu 2020 (Tahun Sekarang) dikurangi dengan Year of Birth, pada source code berikut :

![Gambar](screenshot-pyhton/py2.png)

3. Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen. Outputnya, yaitu dengan syntax/source code berikut :

![Gambar](screenshot-pyhton/py3.png)

Fungsi huruf f pada perintah print(f"...") adalah fungsi print atau bisa memudahkan programmer dalam mencetak statement dalam satu baris.

4. Sedangkan fungsi , pada output tersebut adalah untuk menampilkan hasil dari outputnya Hasil dari output tersebut seperti berikut :

![Gambar](screenshot-pyhton/py5.png)

Selesai Tugas 5 ini.

# TUGAS 6 LAB 1

![Gambar](screenshot-pyhton/py6.png)


Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. Secara default penggunaan end adalah untuk ganti baris. Syntax dibawah ini digunakan untuk menampilkan output berupa string

![Gambar](screenshot-pyhton/py7.png)

Hasilnya :
![Gambar](screenshot-pyhton/py8.png)


Penggunaan Separator Separator adalah pemisah yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda spasi.

![Gambar](screenshot-pyhton/py9.png)

Pendeklarasian beberapa variable beserta nilainya

w,x,y,z=10,15,20,25
Menampilkan hasil dari variable tiap-tiap variable

print(w,x,y,z)
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah , (koma)

print(w,x,y,z,sep=",")
Menampilkan hasil dari tiap-tiap variable tanpa menggunakan pemisah

print(w,x,y,z,sep="")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)

print(w,x,y,z,sep=":")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah -----

print(w,x,y,z,sep="-----")

Hasilnya :

![Gambar](screenshot-pyhton/py10.png)

String Format

String formatting atau pemformatan string memungkinkan kita menyuntikkan item kedalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.

String Format 1 Pada syntax / source code string format 1 akan menampilkan output berupa 2 outputan. Yang pertama (sebelah kiri) akan menampilkan angka Urut dari angka 0 hingga angka 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat. Dengan ketentuan sebagai berikut, operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] )

![Gambar](screenshot-pyhton/py11.png)

Hasilnya : 

![Gambar](screenshot-pyhton/py12.png)

Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10. dengan output sebagai berikut :

![Gambar](screenshot-pyhton/py13.png)

Hasilnya :

![Gambar](screenshot-pyhton/py14.png)


String Format 2 Pada syntax atau source code string format 2 akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri) Dengan ketentuan sebagai berikut : Alignment, padding, dan precesion dengan .format() dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan/kiri, parameter pembulatan dan banyak lagi. Secara Default, .format() menggunakan rata teks ke kiri, angka ke kanan. Kita dapat menggunakan opsi opsional <, ^, atau > untuk mengatur perataan kiri, tengah, atau kanan.

# TUGAS 6 LAB 2

![Gambar](screenshot-pyhton/py15.png)

Disini kita akan menggunakan Penambahan dan Pembagian. Berikuta source code nya.
![Gambar](screenshot-pyhton/py16.png)

Dan ini hasil Outputnya.


![Gambar](screenshot-pyhton/py17.png)

Selesai.

# Terima Kasih 
