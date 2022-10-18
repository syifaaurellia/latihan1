**Hallo nama saya Syifa Aurellia Rahma. Disini saya akan menjelaskan cara penggunaan Git, yang kita perlukan ialah** *Applikasi git, akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan GIT
## Cara penginstalan GIT
- Pertama anda harus mendownload Aplikasi Git, buka website resminya Git di git-scm.com .

![Screenshot (6)](https://user-images.githubusercontent.com/115867244/196310544-cce36f02-5d17-4b16-a7d9-0e1495c54612.png)
*Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support Setelah selesai download klik instal*

- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

![Screenshot (9)](https://user-images.githubusercontent.com/115867244/196310728-e5b24c6e-dd46-4237-b502-1bdea9b6f5ea.png)
- Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1

![195978194-04778e47-f0cd-4d03-9ceb-23394a12b588](https://user-images.githubusercontent.com/115867244/196311099-f32dcaad-5585-41ec-a306-d3de84117fd8.png)
----------------------------------------------------------------------
### _Cara membuat akun git_
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com 

![Screenshot (11)](https://user-images.githubusercontent.com/115867244/196312753-e854ffb7-2a91-4dcb-b7c3-5ee2c592f376.png)
- Pada langka selanjutnya anda boleh langsung diskip saja.
### _Membuat repositori baru_
- Ini adalah tampilan pertama setelah kalian selesai membuat akun git 

![Screenshot (15)](https://user-images.githubusercontent.com/115867244/196313455-e0e49019-503d-4c6c-ad19-b107f949c159.png)
- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

![Screenshot (16)](https://user-images.githubusercontent.com/115867244/196314043-3e570f87-320c-4b45-8696-b2b221868672.png)
- Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub. 

![Screenshot (21)](https://user-images.githubusercontent.com/115867244/196314275-969e426a-950e-4d7b-bfa8-77649b01d009.png)
### _Membuat Repository Local_
- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . 

![195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f](https://user-images.githubusercontent.com/115867244/196315122-4b4e3123-4f9f-4cb8-bf3d-131d0156cfe9.png)
- Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “email_user” $ git config --global user.name “nama_user” 

![Screenshot (23)](https://user-images.githubusercontent.com/115867244/196315447-747d0f95-1664-4b2a-93f3-02634d30b2ab.png)
- Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1". ![Screenshot (27)](https://user-images.githubusercontent.com/115867244/196316528-76da5009-399e-4f2c-b73a-90b9d29df5fe.png)

#### _Cara penggunaan git dengan perintah dasar git init fungsi perintahnya untuk membuat repository local_
- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden. 

![Screenshot (28)](https://user-images.githubusercontent.com/115867244/196324470-3f7fe089-d8af-46f4-9d4c-443b976712fe.png)
- Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

![195979189-8f39f73d-dcea-4d35-982d-d84ddefad965](https://user-images.githubusercontent.com/115867244/196325065-4de74835-5594-463d-bede-4a47a3b35906.png)

#### _Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. 

![Gambar WhatsApp 2022-10-18 pukul 10 27 29](https://user-images.githubusercontent.com/115867244/196329136-2be1fd10-0b69-4009-8b22-0b1f7facb700.jpg)
- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit" 

![195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75](https://user-images.githubusercontent.com/115867244/196329295-e464dbe1-75e1-4844-8f9b-06d88c82e818.png)

##### File berhasil tersimpan
- Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

##### Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/syifaaurellia/latihan1.git

![195979558-eb6c7913-ade9-4381-8584-d3ad396d119f](https://user-images.githubusercontent.com/115867244/196331478-10d49a28-bc8a-41a9-8592-3f9d339e9c29.png)

##### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository 
- Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. 

![195979685-82932b67-cc7a-458a-beb6-4c6a4a12612a](https://user-images.githubusercontent.com/115867244/196332093-66b0eda4-50ff-428d-87e4-8c243d96f105.png)

##### Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/syifaaurellia/latihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"

![195979779-f936d543-9d8c-49e7-8e8c-dcedaa119557](https://user-images.githubusercontent.com/115867244/196332474-2d167090-7ddd-4df9-9899-04db065588a0.png)
- Selesai, jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

### FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.

## Terima Kasih
