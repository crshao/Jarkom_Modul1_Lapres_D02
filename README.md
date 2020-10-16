# Jarkom_Modul1_Lapres_D02
## Laporan Resmi Praktikum Modul 1 Jaringan Komputer 2020
**Kelompok D02**

-Calvin Wijaya 05111840000086

-Alie Husaini R. 05111840000097

##### Nomor 1
Sebutkan webserver yang digunakan pada "testing.mekanis.me"!

```
http.host == testing.mekanis.me
```
![alt img1](image/1.png)

##### Nomor 2
Simpan gambar "Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg"!

```
Export Objects > HTTP > Search "TIM"
```
![alt img2a](image/2a.png)
![alt img2b](image/2b.jpg)

##### Nomor 3
Cari username dan password ketika login di "ppid.dpr.go.id"!

```
http.request.method == POST
```

![alt img3](image/3.png)

##### Nomor 4
Temukan paket dari web-web yang menggunakan basic authentication method!

```
http.authorization contains Basic
```
![alt img4](image/4.png)

##### Nomor 5
Ikuti perintah di aku.pengen.pw! Username dan password bisa didapatkan dari file .pcapng!

```
http.host == aku.pengen.pw
```
![alt img5](image/5.png)

##### Nomor 6
Seseorang menyimpan file zip melalui FTP dengan nama "Answer.zip". Simpan dan Buka file "Open This.pdf" di Answer.zip. Untuk mendapatkan password zipnya, temukan dalam file zipkey.txt (passwordnya adalah isi dari file txt tersebut).

```
ftp-data contains Answer.zip
```
![alt img6](image/6.png)

##### Nomor 7
Ada 500 file zip yang disimpan ke FTP Server dengan nama 1.zip, 2.zip, ..., 500.zip. Salah satunya berisi pdf yang berisi puisi. Simpan dan Buka file pdf tersebut. Your Super Mega Ultra Rare Hint = nama pdf-nya "Yes.pdf"

```
ftp-data
```
![alt img7](image/7.png)

##### Nomor 8
Cari objek apa saja yang didownload (RETR) dari koneksi FTP dengan Microsoft FTP Service!

```
ftp.request.command == RTER (hanya yang Readme)
```
![alt img8](image/8a.png)
![alt img8b](image/8b.png)

##### Nomor 9
Cari username dan password ketika login FTP pada localhost!

```
ftp.request.command == USER || ftp.request.command == PASS
```

![alt img9](image/9.png)

##### Nomor 11
Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!

```
port 21
```
![alt image11](image/11.png)

##### Nomor 12
Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!

```
src port 80
```

![alt img12](image/12.png)

##### Nomor 13
Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!

```
dst port 443
```
![alt img13](image/13.png)

##### Nomor 14
Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

```
ip src 192.168.43.199
```
![alt image14a](image/14a.png)]
![alt image14b](image/14b.png)

##### Nomor 15
Filter sehingga wireshark mengambil paket yang tujuannya ke monta.if.its.ac.id

```
dst host monta.if.its.ac.id
```
![alt img15](image/15.png)
