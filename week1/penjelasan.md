# Week 1
## Download Wireshark
1. Download melalui link berikut : https://www.wireshark.org/#download

<img src="../assets/2.png" width="1000" height="500">

pilih sesuai OS masing2

2. Ini adalah tampilan aplikasi 

<img src="../assets/1.png" width="1000" height="500">

## Menggunakan Wireshark Untuk Proses Penangkapan dan Analisis Lalu Lintas Jaringan
1. Jalankan browser web Anda.
2. Inisialisasi Capture: Memilih antarmuka jaringan Wi-Fi dan memulai perekaman data (Start Capture).

<img src="../assets/4.png">
<img src="../assets/5.png">
<img src="../assets/6.png">
<img src="../assets/7.png">
<img src="../assets/8.png">

3. Saat Wireshark sedang berjalan, masukkan URL: http://gaia.cs.umass.edu/wireshark
labs/INTRO-wireshark-file1.html  dan tampilkan halaman tersebut di browser Anda.

<img src="../assets/3.png">

4. Filtering Data: Perekaman dihentikan (Stop), kemudian filter http diterapkan untuk mengisolasi dan hanya menampilkan paket data yang menggunakan protokol web HTTP.

<img src="../assets/9.png">

5. Identifikasi Paket: Ditemukan paket respons dari server (Paket No. 883) dengan status HTTP/1.1 200 OK, yang menandakan permintaan file berhasil.

<img src="../assets/10.png">

6. Membaca Payload: Pada panel detail paket, bagian Line-based text data diekspansi untuk melihat isi paket. Terlihat jelas source code HTML secara plaintext yang berisi pesan: "Congratulations! You've downloaded the first Wireshark lab file!".

<img src="../assets/11.png">
<img src="../assets/12.png">
