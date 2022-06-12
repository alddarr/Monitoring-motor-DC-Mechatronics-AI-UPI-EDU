# Monitoring-motor-DC-Mechatronics-AI-UPI-EDU
Repository ini merupakan dokumentasi projek UAS mata kuliah Sensor dan Tranduser.

Anggota Tim :

Geralda Livia Nugraha (2100179)

RAMADHIRRA AZZAHRA PUTRI (2100188)

Vinka Reviansa (2101918)

MUHAMMAD WILDAN ALFARIZY (2106373)

MUHAMMAD MIZANULKHAIR (2107620)

I. Monitoring Arus, Daya, Tegangan dan Kecepatan Motor DC Menggunakan NodeMCU ESP8266 Yang Terintegrasi Dengan Database Mysql

II.Latar Belakang

Seiring Perkembangan teknologi memungkinkan dibuat perangkat pengendali dengan ukuran yang kecil tetapi memiliki kemampuan komputasi, kecepatan, dan keandalan sertaefisiensi yang tinggi. salah satunya yaitu pengendali motor DC yang banyak digunakan dalam berbagai bidang mulai dari peralatan industri sampai rumah tangga. pada praktikum kali ini kami akan menggunakan sistem hardware yang terdiri dari Sistem hardware terdiri NodeMCU ESP8266 , Sensor INA219 dan Speed Sensor LM393. Sistem hardware berfungsi untuk mengukur Tegangan dan Arus (Sensor INA219) dan mengukur kecepatan motor (Sensor LM393) kemudian nilai yang dibaca oleh sensor akan diolah datanya pada NodeMCU ESP8266 setelah itu NodeMCU ESP8266 akan mengirim datake database MySQL. 
 
 IV. Analisis dan Diskusi Project
1. Pertama NodeMCU ESP8266 akan menghubungkan jaringan ke wifi dan server. Jika 
tidak terhubung maka akan dilakukan konektivitas ulang hingga NodeMCU 
terhubung, jika terhubung maka akan dilakukan langkah selanjutnya.
2. Selanjutnya NodeMCU akan mendeteksi apakah sensor INA219 dan LM393 sudah 
terhubung dengan baik dan inisialisasi pin sensor.
3. Selanjutnya Sensor INA219 akan membaca nilai tegangan dan arus dan sensor LM393 
akan membaca nilai kecepatan.
4. Selanjutnya NodeMCU ESP8266 menerima data dari sensor dan mengolah data sensor
5. Selanjutnya NodeMCU ESP8266 mengirim data sensor ke database MySQL
6. Langkah terakhir Menampilkan data nilai pembacaan sensor pada Website.

Dari perancangan dan pengujian aplikasi monitoring yang telah dilakukan, terhadap fitur-fitur pada sistem monitoring berbasis website, semua fitur dapat berjalan sebagaimana mestinya. Monitoring arus, tegangan, daya dan kecepatan motor secara otomatis menggunakan sensor INA219 dan speed sensor LM393 dan mengirimkan ke database Mysql. Data dikirim dari database ke Web menggunakan software Visual Code dengan menggunakan bahasa HTML dan CSS dan menghasilkan tampilan nilai dan grafik hasil pengukuran .

 V. Referensi
 
• https://www.nyebarilmu.com/apa-itu-module-nodemcu-esp8266/#:~:text=NodeMCU%C2%A0ESP8266%C2%A0merupakan%20modul%20turunan%20pengembangan%20dari%20modul%20platform%20IoT,yang%20membedakan%20yaitu%20dikhususkan%20untuk%20%E2%80%9CConnected%20to%20Internet%E2%80%9C.

• https://kelasrobot.com/apa-itu-nodemcu-esp8266-bagaimana-cara-pakenya/

• https://www.nn-digital.com/blog/2019/06/09/belajar-modul-ina219-sensor-arus-tegangan-daya-dengan-arduino/

• https://siddix.blogspot.com/2019/02/pengertian-dan-cara-kerja-ic-komparator.html

• https://www.mahirelektro.com/2020/02/tutorial-menggunakan-driver-motor-l298n-pada-Arduino.html
 
 
