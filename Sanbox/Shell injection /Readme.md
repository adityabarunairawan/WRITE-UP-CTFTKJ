## Shell Injection
**Pada soal ini apakah kamu tau command injection ?, ini konsepnya sama dengan shellbox di TCP1P dan kita di kasih Ip dan port untuk koneksi ke server netcat**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/15bc0e4d-1e1e-4d3a-be6c-31271703554f)

**Kemudian saya mencoba melihat isi dari sanbox dengan menggunakan command injection payload dengan command ‘; ls ;’ saya mencoba melihat isi dari flag.txt ternyata tidak ada isi sama sekali dan saya coba melihat isi dari hex ternyata ada beberapa file yang ada di dalam hex tersebut**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/368e9d63-244b-4782-811f-610f59ae88c7)

**Kemudian saya ingin melihat isi dalam flag.txt tersebut dengan perintah ‘; cat flag.txt ;’ dan boom ternyata saya mendapatkan flag yang tersembunyi di dalam sanbox tersebut**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/0febbbd9-8a0d-46d2-bfa3-2b603331b920)

**FLAG:W9{**************************}**
