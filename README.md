## Latihan1 

## TUGAS BAHASA PEMROGRAMAN

## INSTALASI GIT
Membuka website resmi GIT yaitu (git-scm.com), lalu mendownload sesuai OS 

## MEMBUKA GIT BASH
Setelah mendownload lalu membuka GIT BASH

## MENAMBAHKAN GLOBAL CONFIG
Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
Konfigurasi ini bisa dilakukan untuk globab repositiry atau indovidual repository.
Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
Config Global Repository

## MEMBUAT REPOSITORY LOCAL
Buka direktory aktif, misal: /d/praktikum1

mkdir praktikum1
cd praktikum1

## MENJALA…
ik tombol start a project, atau dari menu (icon +) klik New Repository

## MEMBUAT REPOSITORY SERVER
Isi nama repositorynya, misal:nomnom.
Lalu klik tombol Create repository

## MENAMBAHKAN REMOTE REPOSITORY
Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
untuk menambahkan remote repository server, gunakan perintah

git remote add origin [url]
git remote add origin https://github.com/Galihh1/latihan1.git


## MENGIRIM PERUBAHAN KE SERVER (PUSH)
Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.

git push -u origin master


perintah ini akan meminta memasukkan username dan password pada akun github.com

## CLONE REPOSITORY
Untuk melakukan cloning,gunakan perintah :

git clone [url]
