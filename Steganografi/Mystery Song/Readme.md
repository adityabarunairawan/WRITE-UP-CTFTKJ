## Mystery Song 
**Pada soal ini kita di suruh menemukan kata rahasia di dalam music tersebut lalu kita di suruh mengartikan kata rahasia dari musik tersebut.**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/7bae4ee5-afc0-4f7a-a2b7-fa28cb865055)

**Kita di kasih hint “Saat kalian ektraks kalian akan di mintai password silahkan kosongi password nya**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/8a78863f-c726-48b3-88ad-a9efe6289450)

**Saya mencoba mengekstrak Music tersebut dengan coomand/tools _steghide extraxt -sf {nama file}_ dan saya di suruh memasukan password namun di dalam hint tersebut saya di suruh mengosongi password tersebut dan saya mendapatkan file yaitu “secret.txt”**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/1e57748a-b38c-4f78-b7d1-f2956ce062fa)

**Saya lalu membuka file yang ada didalam secret.txt dan saya menemukan teks format Base64**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/2372f66d-dfbd-4e9c-9660-3b675854d972)

**Kemudian saya mencoba decrypt teks yang berformat base64 dan saya mendapatkan flag tersebut.**

![image](https://github.com/adityabarunairawan/WRITE-UP-CTFTKJ/assets/136324726/d1c66f21-c163-43c8-b27b-e2149e08b373)

**FLAG:W9{*****************}**
