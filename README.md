# Jarkom-Modul-1-IT22-2023
```
Rakha Aldo Nirwasita - 5027211054
Reynold Putra Merdeka - 5027211034
```
## Soal No 1

![988e9643-b216-4e86-8b13-a1375d9eaf7e](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/872f8614-fd59-44e0-aa70-31e4f82a273a)

User melakukan berbagai aktivitas dengan menggunakan protokol FTP. 

1# mula - mula kami mencari pada wireshark dengan query ```ftp || ftp-data``` dan wireshark akan memberikan hasil dimana akan memfilter yang menggunakan protocol FTP

2# kemudian kami temukan beberapa pertanyaan seperti pada digambar

A. Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut?

B. Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut?

C. Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

D. Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

<img width="616" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/cdc5799b-ef7d-422d-aa2c-23cd384004ee">

3# Jawaban
### A. Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut?
1. ditemukan sebuah peritah **STOR** pada packet yang bermakna adanya perintah untuk **melakukan sebuah pengiriman file** melalui protocol FTP
2. pada terminal, kami temukan jawaban nya yakni ``` 258040667``` 

### B. Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut?
1. pada tempat yang sama ditemukan di tempat yang sama
2. dan ditemukan jawabannya yakni ```1044861039 ```

### C. Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
1. pada no ini ditemukan pada package 149 dimana terpapat **response 150** dimana itu merupakan feedback dari **STOR**
2. maka diperoleh hasil untuk c yakni ```1044861039```

### D. Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
1. pada soal ini ditemukan pada tempat yang sama di package yang sama
2. diperoleh hasil yakni ```258040696```


dan diperoleh flag yakni ``` Jarkom2023{y0u_r_g00d_4t_4dr3ssing_JzBrEwA81241276}```

## Soal No 2

![9253cdf4-2b1c-4d7d-8645-a75caf56599c](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/1bb47cac-cecd-4916-add7-6cd142225a90)

peserta diminta untuk **mencari web server** yang digunakan pada **portal Praktikum Jaringan Komputer**

**JAWAB**
1. diunduh **soal2.pcap** 
2. masukan query dan ketik **"http"** dan akan memberikan hasil sesuai pada gambar

<img width="409" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/db347841-7715-443c-aa69-2d58ce416fcb">

3. dan kemudian di click pada yang berprotocol **"HTTP"** dan dicari servernya
4. dan ditemukan servernya yakni ```gunicorn```

dan ditemukan flag nya yakni ```Jarkom2023{9unic0rn_1s_N2Dc6LS8eq41p3g_c00l}```

## Soal No 3


 ![faad947f-c68a-426f-b164-3bc22179ca68](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/bd0c7454-e2fc-426b-a487-f5551074a5c9)
 

 Pada soal kali ini kami diberikan sebuah perintah untuk membantu mas dafin dalam memperlajari soal pada nc yang tertera

 1. diunduh file **soal3.pcap** 
 2. dimasukkan query yang diperlukan dalam untuk memfilter pada wireshark yakni ```ip.addr == 239.255.255.250 && udp.port == 3702```
 3. fungsi dari ```ip.addr == 239.255.255.250``` yakni untuk memperoleh package dengan ip tujuan atau dari ```239.255.255.250```
 4. fungsi dari ```udp.port == 3702``` yakni untuk memperoleh port UDP menuju atau dari port ```3702```
 5. dan diperoleh hasilnya terdapat 21 package
    
    
<img width="503" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/6f46f7d5-505b-4691-a4c6-485d762a5607">



6. terdapat pertanyaan pada terminal saat memasukan nc pada terminal yakni:
   A. berapa banyak jumlahnya: 21
   
   B. protokol ayer transport yg digunakan: UDP


dan diperoleh flag yakni ```Jarkom2023{4nalyz3_is_1030_FjCgRkAiRkD_gr3at}```




## Soal No 4


![b1053e99-233f-4a99-9c82-b431f0f42c01](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/9036ffcc-c017-425e-bc84-2e8f4a84da79)


peserta diminta untuk mencari **checksum** dari **package ke 130**

**JAWAB**

<img width="503" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/a3f81d42-cfa7-41ff-b2a5-bf3265e06d77">


1.Di unduh **soal4.pcap** 
2.cari untuk **package no 130** pada tulisan **nomor paling kiri**
3.klik dan **cari check sum** dari **package 130**
4.dan dimasukkan check sum kedalam nc yang tertera dan dimasukkan no checksum yang diperoleh yakni ```0x18e5```

diperoleh flag yakni ```Jarkom2023{ch3cksum_is_u5eful_0x5k2k}```
 



## Soal No 5


![26e933fa-2148-4f3d-8ccc-5eba118ce8e0](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/b86e3206-acce-4ce1-811d-6daa4359fd14)


**JAWAB**
1. Di unduh **soal5.pcap**

   

<img width="505" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/885dcf04-aae5-4497-816e-6c10c1afb1d2">



2. kemudian hasil yang diperoleh dimasukkan kedalam terminal dengan nc yang tertera yang didalamnya terdapat beberapa pertanyaan yakni:
  A. berapa banyak package yang berhasil dicapture dari file pcap: ```60```

  B. port berapakah yang digunakan pada service SMTP: ```25```
  
  C. dari semua ip yang tercapture, ip berapakah yang public: ```74.53.140.153```


<img width="506" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/7ab20005-bcda-4e48-b4e8-3e0a776633fa">



dan diperoleh flag yakni ```Jarkom2023{k0w4lski_8121_zyvOEtExABB_4nalys1s}```


## Soal No 7



![2199e07a-65a7-445e-b214-71f99d3b8ce3](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/aab03725-76a1-4fb6-8c11-c84a52a188c5)



diberikan pertanyaan untuk mencari jumlah package yang mengarah ke ip ```184.87.193.88```

**JAWAB**
1. Di unduh **soal7.pcap**
2. dimasukan query untuk memfilter hasil menuju ke ip terkait yakni ```ip.dst == 184.87.193.88```
3. kemudian hasil tersebut dimasukkan kedalam terminal dengan nc pada soal



<img width="505" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/fa049675-fa2c-4be2-80f7-312fb7b6b565">



diperoleh flag yakni ```Jarkom2023{ajCG121SCUCj6J7vJ0_4n0th3r_f1lt3ring}```







## Soal No 8
diberikan soal diperintahkan untuk memfilter **package yang menuju port 80** (jika lebih dari satu maka diurutin)



![6c1cddec-6843-4391-9804-55c51849e35f](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/bab7966b-f6f0-435f-8c59-45d61b83e3d6)



**JAWAB**

1. dimasukan query untuk memfilternya yakni ```tcp.dstport == 80 || udp.dsport == 80```
2. diperoleh hasil sebanyak **6 package**
   

<img width="500" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/3e5575b8-767e-424d-884d-70d5eeb873cf">


3. hasil dimasukkan kedalam nc terminal 

diporoleh flag yakni ``` Jarkom2023{qu3ryyyyying_880375_BmOtOxOhSwN_15_fun}```


## Soal No 9


![eec63d25-3c1c-4a92-ac42-2f485ec95fe5](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/db876da3-6ea3-4ae7-9d3d-55d38e795e99)


**JAWAB**


<img width="502" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/878eeeee-ec4e-4e42-9f09-3e0df65d344a">



## Soal No 10


![cf54b319-ccc3-4dbf-9d75-eb513b6966e5](https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/baf10022-1958-4490-ada8-a0cae4b9e370)


**JAWAB**

<img width="501" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/38466fe4-cfe9-41d1-b211-d9cc42c7e965">


<img width="503" alt="image" src="https://github.com/Callmerakha/Jarkom-Modul-1-IT22-2023/assets/103549279/6be9308e-ebbb-42a5-8ea9-2b1a0b35953d">


