# Rifaldi-Syafikri-Abdullah--Project-2
project 2 
nama : Rifaldi Syafikri Abdullah 
kelas : SI A 25 
NIM : 05301425019
MK : SISTEM OPERAS

Project 2: Network Diagnostic Tool

Tujuan Project

Membuat script sederhana untuk mendiagnosis masalah jaringan menggunakan perintah CMD, sehingga pengguna dapat mengetahui kondisi IP, koneksi internet, jalur routing, dan koneksi aktif.


---

Langkah-Langkah

1. Cek Konfigurasi IP

Gunakan perintah:

ipconfig /all

Fungsi:

Menampilkan detail jaringan: IP, DNS, Gateway, MAC Address.

Mengecek apakah perangkat mendapatkan IP yang benar.

https://drive.google.com/drive/folders/1ty3eq-jcZnPJujBQafjtaHQ8pUQc54jH

---

2. Test Koneksi Internet

Gunakan:

ping 8.8.8.8

Tujuan:

Mengecek apakah perangkat bisa terhubung ke internet global.

8.8.8.8 = DNS milik Google yang sangat stabil.
https://drive.google.com/drive/folders/165GLShuV9mxOOU15546E3QFjK7vWfZOn


---

3. Cek Koneksi ke Website

Gunakan:

ping google.com

Fungsi:

Mengecek apakah DNS bekerja dengan benar.

Mengetahui delay ke alamat domain.


Jika ping 8.8.8.8 berhasil tapi ping google.com gagal → masalah DNS.
https://drive.google.com/drive/folders/19cy3qWo2w-kOeb8URtGA9w21rl8QOYcz

---

4. Trace Route

Gunakan:

tracert google.com

Tujuan:

Mengetahui jalur yang dilalui paket sampai ke server tujuan.

Berguna untuk menganalisis hambatan di tengah jaringan.

https://drive.google.com/drive/folders/19cy3qWo2w-kOeb8URtGA9w21rl8QOYcz

---

5. Lihat Koneksi Aktif

Gunakan:

netstat -an

Fungsi:

Menampilkan semua port dan koneksi aktif.

Mengecek apakah ada koneksi mencurigakan atau penggunaan port yang tidak normal.

https://drive.google.com/drive/folders/1Xon1a5MddsZyyvcjX204_t_ddLuncME2

