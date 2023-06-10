# UAP_ADSIS_E_Dhimas
1\. Buat direktori dengan nama UAP-Adsis, isi dengan file txt dengan format penamaan catatannya-nama kamu>.txt, kemudian isi file txt tersebut dengan nama dan NIM kamu. Kemudian atur permission view-only pada file tersebut untuk user biasa. Tunjukkan bukti berupa screenshot yang menunjukkan bahwa file tersebut berhasil diatur permissionnya menjadi view-only untuk user biasa.

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.001.png" >
</p>
<p align="center">Gambar 1.1</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.002.png" >
</p>
<p align="center">Gambar 1.2</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.003.png" >
</p>
<p align="center">Gambar 1.3</p>

Pada Gambar 1.1 menggunakan perintah mkdir UAP Adsis untuk membuat directory baru dan membuat file baru dengan perintah sudo touch catatannya-dhimas.txt, kemudian isi file txt tersebut dengan cara sudo nano catatannya-dhimas.txt, lallu isi nama dan NIM sesuai pada gambar 1.2 . Kemudian mengatur permission view-only pada file tersebut menggunakan perintah chmod 400 catatannya-dhimas.txt dan untuk melihat apakah sudah benar permission file tersebut sesuai dengan perintah soal, maka kita gunakan ls -l catatannya dhimas.txt. Pada gambar maka sudah terlihat bahwa permissionnya berhasil diubah.

2\. Lakukan konfigurasi alamat IP address sementara pada sistem dan default gateway. (petunjuk 192.168.56.x | x adalah nomor absen)

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.004.png" >
</p>
<p align="center">Gambar 2.1</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.005.png" >
</p>
<p align="center">Gambar 2.2</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.006.png" >
</p>
<p align="center">Gambar 2.3</p>

Untuk konfigurasi alamat IP address sementara pada sistem dan default gateway. Saya menggunakan IP 192.168.56.3, untuk mengubah ip sementara saya menggunakan perintah sudo ifconfig ens33 192.168.56.3. Lalu mengecek apakah ip saya sudah berubah menggunakan perintah ifconfig. Setelah itu saya melakukan sudo route add default gw 192.168.56.3 untuk mengubah default gateway nya, pada gambar ketiga sudah terlihat bahwa default gateway berhasil diubah. 

3\. Lakukan Instalasi Webmin lalu buatlah user bemama nama anda, lalu buat group Adsis (kelas masing-masing) dan masukkan nama anda di group

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.007.png" >
</p>
<p align="center">Gambar 3.1</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.008.png" >
</p>
<p align="center">Gambar 3.2</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.009.png" >
</p>
<p align="center">Gambar 3.3</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.010.png" >
</p>
<p align="center">Gambar 3.4</p>

Pada gambar pertama terlihat bahwa user dengan nama saya “dhimas” sudah terdaftar pada webmin yang sudah diinstal. Lalu pada gambar kedua saya membuat group baru dengan nama ADSIS\_E. Pada gambar ketiga, saya mengubah group dari user “dhimas” menjadi ADSIS\_E, kemudian saya mengecek dengan perintah ls -l /home/ pada terminal dan pada gambar keempat terlihat bahwa group dari user “dhimas” berhasil diubah.

4\. Lakukan ping ke alamat ip anda dan coba lakukan reject dan drop di webmin, lalu analisis apa yang terjadi?

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.011.png" >
</p>
<p align="center">Gambar 4.1</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.012.png" >
</p>
<p align="center">Gambar 4.2</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.013.png" >
</p>
<p align="center">Gambar 4.3</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.014.png" >
</p>
<p align="center">Gambar 4.4</p>

Pada gambar pertama, saya melakukan ping ke ip 192.168.56.3 dan berhasil. Lalu pada gambar kedua saya mengubah linux firewall pada webmin dimana Pada paket input konfigurasi Set Default Action To dengan nilai Drop, dilanjutkan pilih Add Rule. Lakukan konfigurasi pada: Action to take dengan memilih Reject, Reject with ICMP type dengan memilih Type dengan nilai icmp-net-unreachable dan pada Network Protocol dengan memilih Equals dengan nilai ICMP. Pada gambar ketiga, adalah tampilan setelah setelan berhasil di konfigurasi, lalu apply configuration dan lakukan ping pada terminal. Pada gambar keempat terlihat bahwa paket semuanya berhasil di reject oleh firewall linux.

5\. Buatlah perintah otomatis yang berfungsi untuk ping [www.filkom.ub.ac.id](http://www.filkom.ub.ac.id)

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.015.png" >
</p>
<p align="center">Gambar 5.1</p>

<p align="center">
  <img src="https://github.com/DhimasBagusB/UAP_ADSIS_E_Dhimas/blob/main/Images/Aspose.Words.aba7ae09-88c8-4168-a25f-70eeb2085001.016.png" >
</p>
<p align="center">Gambar 5.2</p>

Lakukan perintah sudo crontab -e kemudian tambahkan di baris akhir:

\*/2 \* \* \* \* ping filkom.ub.ac.id

Ini artinya setiap 2 menit user akan melakukan ping ke web filkom.ub.ac.id, kemudian kita dapat melihatnya dengan perintah ps -aux | grep ping  untuk melihat hasil ping yang telah dilakukan. Maka, terlihat pada gambar terakhir kita sudah berhasil melakukan ping otomatis ke filkom.ub.ac.id setiap 2 menit sekali
