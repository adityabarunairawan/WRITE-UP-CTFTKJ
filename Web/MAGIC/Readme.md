## MAGIC
**pada soal Web magic ini kita di kita di kasih sebuah link dan soal namun soal tersebut mungkin itu adalah hint buat kita untuk mencari flag yang tersembunyi tersebut Apakah kamu tau strcmp?**

![MAGIC](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/533ecc62-e47a-4d2e-a8b4-0c84a4c63e5c)

**Kemudian saya mencari tau apa itu strcmp itu ternyata adalah Fungsi strcmp() digunakan untuk membandingkan string dengan string yang lainnya. Fungsi strcamp() akan menghasilkan nilai 0 apabila kedua string yang dibandingkan sama. Tapi kalau berbeda akan menghasilkan angka yang berbeda-beda.Di soal ini kita di berikan link website tersebut ada source code php dan ini adalah php type jungling**

![MAGIC2](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/bfd5bce2-cafd-4417-9193-e2a3f2a6eb5b)

**Dalam PHP, fitur "Type Juggling" memungkinkan konversi otomatis antara tipe data saat operasi atau evaluasi ekspresi. Parameter dalam fungsi PHP yang berkaitan dengan Type Juggling dapat digunakan untuk mengontrol perilaku konversi tipe,Dengan menggunakan tipe data pada parameter, Anda dapat mengatur tipe data yang diharapkan untuk parameter tersebut, dan PHP akan melakukan konversi otomatis sesuai dengan peraturan Type Juggling.**

![MD5](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/5cd90ffa-ea56-4903-a011-36c8f921d8c9)

**Kemudian saya mencoba menambahakan x dan y dengan md5 seperti gambar di bawah ini**
![PARAMETER](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/369cb0ab-0879-434e-9214-be9e89b88b2b)

**dan saya berhasil mendapatkan flag tersebut karena saya mengirimkan parameter yang sesuai dari permintaan source code tersebut**

![flag](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/823ff4c6-e42b-494c-a68a-bac4a9c82569)

**FLAG:W9{***************************}**
