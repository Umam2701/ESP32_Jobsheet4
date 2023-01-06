# JOBSHEET 4 - EMBEDDED SYTEM

Pada jobsheet 4 ini kita menggunakan sensor untuk membaca data yang kemudian di kirim ke database.

**HASIL PERCOBAAN :**


*A. ESP32--> Cayenne (MQTT)(sensor+LED)(on/off)--> button mobile monitoring*

<img width="609" alt="job 4" src="https://user-images.githubusercontent.com/121012286/210361665-13ae2e6f-018a-411c-824b-d2735e8f256e.png">

Output :

https://user-images.githubusercontent.com/121012286/210361729-d527e46d-7772-4977-ac7a-4ead799d7362.mp4

*Analisa :* Berdasarkan hasil percobaan di atas, memiliki output yang sudah sesuai dengan program yang telah di input, di mana lampu LED pada rangkaian akan on dan off apabila tombol pada website cayenne diklik. Artinya semua aktifitas dikontrol pada `Website Cayenne` karena semua database disimpan pada website tersebut.

<br>

*B. ESP32 --> Adafruit IO (MQTT) --> Sensor + LED (on/off) --> Suara di Google Assistan*

![image](https://user-images.githubusercontent.com/121012286/210932826-b0230098-9f5c-4399-a211-2ffcff5ac8ab.png)

![image](https://user-images.githubusercontent.com/121012286/210932844-5923e8c6-afd2-49f9-b067-0c9ff4bf52ae.png)

![image](https://user-images.githubusercontent.com/121012286/210932884-070680e2-a6f1-4e45-b3cd-b4082061a005.png)

*Analisa :*  Untuk menghasilkan output seperti di atas, membutuhkan library adafruit IO (MQTT) yang kemudian ditambahi LED sebagai indikator untuk mengetahui apakah sensor tersebut bekerja. Kemudian data disimpan ke database lalu `Google Assistan` yang akan mengendalikannya.


*C. ESP32 --> ThingSpeak (HTTP/REST) --> Sensor*

![image](https://user-images.githubusercontent.com/121012286/210932949-5974fe32-5b78-4c88-8ca8-8e40d530bfb3.png)

![image](https://user-images.githubusercontent.com/121012286/210933010-cdacbf23-36af-431f-84eb-7e1cab533510.png)

*Analisa :* Dari percobaan yang ketiga ini menggunakan sensor DHT 11 untuk membaca suhu dan kelembapan udara. Data dari sensor kemudian di kirim ke ThingSpeak untuk menampilkan data yang dibaca oleh sensor tadi. Data yang ditampilkan berupa chart atau diagram.

*D. ESP NOW + IoT*

![image](https://user-images.githubusercontent.com/121012286/210933042-42dab020-68b3-49c5-b5e1-49a4eca6312c.png)

![image](https://user-images.githubusercontent.com/121012286/210933067-88bdad6b-4f0a-42a7-848f-4b95ff3e166d.png)

![image](https://user-images.githubusercontent.com/121012286/210933089-37f0c040-716b-4ed0-92a7-76ac38e6f9be.png)


