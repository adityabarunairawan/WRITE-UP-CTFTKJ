# the magic php power full #
pada soal ini kita disuruh meneliti source code dari sebuah website yang sudah diberikan

![1](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/d383d208-9991-4c80-81e7-2564a9c72de9)

pada web tersebut kita disuruh membuka source code tersebut kemudian saya buka source code tersebut menggunakan CTRL+U

![2](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/abb1cd39-114c-4108-9e45-37dc796e9beb)

ternyata ada sebuah parameter ?src pada source code tersebut

![3](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/f5f7fc32-ef47-46d2-9d62-eac9108cf730)

code ini adalah code php type jungling pada code tersebut code (if(file_get_contents($_GET['0']) === 'welcome CTF TKJ')): = welcome CTF TKJ adalah mengecek isi dari file yang diberikan code, code (if(intval($_GET['1']) === $_GET['2'] || $_GET['1'] !== $_GET['2'])): mengecek interger dari parameter GET jika kunci 1 sama dengan nilai dari parameter GET dengan kunci 2 atau jika tidak sama code (if(!strcmp($_GET['3'], rand()))): mengecek apakah string dari parameter GET dengan kunci 3, Jika semua diatas terpenuhi maka akan mengasikan file flag.php dalam code 

![4](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/84eacfba-da1e-497f-972f-93b604b8e3bf)

Dalam PHP, fitur "Type Juggling" memungkinkan konversi otomatis antara tipe data saat operasi atau evaluasi ekspresi. Parameter dalam fungsi PHP yang berkaitan dengan Type Juggling dapat digunakan untuk mengontrol perilaku konversi tipe,Dengan menggunakan tipe data pada parameter, Anda dapat mengatur tipe data yang diharapkan untuk parameter tersebut, dan PHP akan melakukan konversi otomatis sesuai dengan peraturan Type Juggling.

![5](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/ef38909a-ab50-47c8-a097-a9fcf1ca1cfd)

Kemudian saya menambahkan 0=data;,welcome CTF TKJ 1 dan 2 saya tambahkan md5 dan 3 saya tambahkan [] karena strcmp lambangnya []

![6](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/f4b8bcbe-91e1-4bc6-9d19-e3c3439e12aa)

dan saya berhasil mendapatkan flag, jika parameter yang sesuai dari permintaan source cod tersebut maka akan menghasilkan sebuah flag

![7](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/818d7c23-b49b-422c-8f72-951747af00a2)


**FLAG:W92{*****************************)**
