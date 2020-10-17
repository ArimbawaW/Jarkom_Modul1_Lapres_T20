# Jarkom_Modul1_Lapres_T20

## Anggota Kelompok
- 05311840000040 Ghifari Akbar Rabbani
- 05311840000045 I Gede Arimbawa Teja Putra Wardana

## No. 1

Untuk mengetahui webserver yang digunakan "testing.mekanis.me" pertama melalui display filter `'http.request http.host eq "testing.mekanis.me"'` dari hasil display filter pertama diexpand pada bagian "Hypertext Transfer Protocol" diketahui response dari packet berada pada packet nomor 21251. Melihat dan mengexpand packet 21251 terdapat 'Server'yang digunakan yaitu nginx/ubuntu.

### Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/1.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/1.1.png)




## No. 2

Melalui File -> Export Objects -> HTTP dan mencari nama file "Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg" 

### Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/2.1.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/2.png)


## No. 3

Untuk mengetahui login di situs http://ppid.dpr.go.id/ pertama harus melakukan display filter menggunakan command `http.request.method == POST` dari situ lakukan Follow TCP Stream pada packet dan akan terlihat username 10pemuda dan password guncangdunia.

### Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/3.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/3.1.png)


## No. 4

Melihat semua website yang menggunakan *basic authentication method* dapat dilakukan dengan mudah yaitu menggunakan display filter `http.request.uri contains "login"` 

### Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/4.png)


## No. 5

Lakukan display filter untuk situs aku.pengen.pw dengan `http.request and http.host eq "aku.pengen.pw"` dan pada packet 31651 terdapat Credentials yaitu username dan password. Masuk ke situs aku.pengen.pw dan masukkan username dan password

### Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/5.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/5.1.png)



## No. 6

Seseorang menyimpan file zip melalui FTP dengan nama "Answer.zip". Simpan dan Buka file "Open This.pdf" di Answer.zip. Untuk mendapatkan password zipnya, temukan dalam file zipkey.txt (passwordnya adalah isi dari file txt tersebut).

### Screenshot

 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/fbcac4d64e817ffc1c5c82fecdcaa6cc62904322/6.png)
 
 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/fbcac4d64e817ffc1c5c82fecdcaa6cc62904322/6.1.png)
 
 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/fbcac4d64e817ffc1c5c82fecdcaa6cc62904322/6.2.png)



## No. 7
Ada 500 file zip yang disimpan ke FTP Server dengan nama 1.zip, 2.zip, ..., 500.zip. Salah satunya berisi pdf yang berisi puisi. Simpan dan Buka file pdf tersebut.

Kita bisa mendapatkan file yang berisi Yes.pdf dengan menggunakan ftp-data contains "Yes.pdf"

### Screenshot

 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(335).png)
 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(336).png)

## No. 8

Cari objek apa saja yang didownload (RETR) dari koneksi FTP dengan Microsoft FTP Service!

Dengan menggunakan Display Filter `ftp-data contains "ftp.cdc.gov"` dimana `"ftp.cdc.gov"` adalah situs website yang digunakan Microsoft FTP Service untuk mendownload file

### Screenshot
 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(355).png)
## No. 9

Cari username dan password ketika login FTP pada localhost!
kita bisa mendapatkan username dan password dengan cara ftp.request.command contains "USER" || ftp.request.command contains "PASS"

## Screenshot

 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/no9.png)


## No. 10

Cari file .pdf di wireshark lalu download dan buka file tersebut!
clue: "25 50 44 46" 

Kita bisa mendapatkannya dengan 

## Screenshot

 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(340).png)
 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(341).png)




## No. 11

Capture filter yang digunakan untuk melihat packet yang mengandung port 21 adalah `tcp port 21`
kita bisa menghubungkan dengan filezilla lalu kita bisa masukkan port 21

 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(351).png)
 ![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(350).png)

## Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/11.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/11.1.png)


## No. 12

Capture filter yang digunakan untuk melihat packet yang berasal dari port 80 adalah `src port 80`

## Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/12.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/12.1.png)
 
 
## No. 13

Capture filter yang digunakan untuk melihat packet yang menuju port 443 adalah `dst port 443`


## Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/13.png)
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/gambar/13.1.png)


## No. 14
Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!
kita bisa mencari ip kita melalui cmd lalu kita bisa masukkan src (ipyangdidapat)

## Screenshot
![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(342).png)

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(343).png)


## No. 15

Filter sehingga wireshark hanya mengambil paket yang tujuannya ke monta.if.its.ac.id!
kita bisa mendapatkan dengan menggunakan command host

## Screenshot

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(344).png)

![Alt text](https://github.com/ArimbawaW/Jarkom_Modul1_Lapres_T20/blob/main/Screenshot%20(345).png)


