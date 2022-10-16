## tugas1

# tugas bahasa pemrogaman

## download git
membuka website resmi git (git-scm.com), lalu diinstal sesuai leptop yang digunakan
![gambar1](gambar/azra1.png)

## membuat git bash
setelah itu membuka git bash
![gambar2](gambar/azra2.png)

## membuat global config
pada saat pertama kali menggunakan git, kita perlu melakukan konfigurasi user,name dan user.email., konfigurasi ini bisa dilakukan untuk global repostiriy atau individual repository atau individual repository. bila belum dilakukan konfigurasi,akan menakibatkan terjadinya kegagalan saat menjalankan perintah git commit
config global repository
```
$ git config --global user.name "nama_user"
$ git config --global user.email "nama_email"
```
![gambar3](gambar/azra3.png)

## membuat repository local
buat direktory projec praktikum pertama dengan nama tugas1
```
$ mkdir tugas1
$ cd tugas1
```
![gambar4](gambar/azra4.png)
sehingga terbentuk satu direktori baru dibawahnya,selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)

jalankan perintah git init,untuk membuat repository local.
```
$ git init
```
![gambar5](gambar/azra5.png)
## menambahkan file baru pada repository
disini kita akan mencoba buat satu file bernama README.md(text file)
```
$ echo "# tugas 1" >> README.md
```
![gambar6](gambar/azra6.png)

untuk menambahkan file yang baru saja di buat tersebut gunakan perintah gut add.
```
$ git add README.md
```
![gambar7](gambar/azra7.png)

## menyimpan perubahanke database
untuk menyimpan perubahan yang ada ke dalam database repository local,gunakan perintah :
```
$ git commit -m "simpan"
```
![gambar8](gambar/azra8.png)

## membuat repository server
anda harus membuat akun di github terlebih dahulu
pada halaman github,klik tombol start a prooject atau
darimnu (icon +) klik new repository
![gambar9](gambar/azra9.png)

isi nama repositorynya, misal:tugas1
lalu klik tombol create repository
![gambar10](gambar/azra10.png)

## menambahkan remote repository
gunakan perintah :
```
$ git remote add origin [url]
```
![gambar11](gambar/azra11.png)

## mengirim perubahan keserver (push)
untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
``` 
$ git push -u origin master
```
![gambar12](gambar/azra12.png)

## melihat hasil pada server repository
untuk buka halaman github.com,arahkan pada repositorynya
![gambar13](gambar/azra13.png)

## clone repository
pada dasarnya mengcopy repository server dan secara otomatis mebuat satu direktory sesuai dengan nama repositorynya (working directory)
untuk melakukan cloning,gunakan perintah :
```
$ git clone [url]
```
![gambar14](gambar/azra14.png)
