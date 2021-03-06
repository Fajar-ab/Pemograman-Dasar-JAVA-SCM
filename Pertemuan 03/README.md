# Pertemuan 3

### STMIK Citra Mandiri Padangsidimuan

**Parodi**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;Sistem Informasi <br>
**Jumlah Sks**&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;3SKS <br>
**Lembaran**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;Job Sheet 3 <br>
**Matakuliah**&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;Bahasa Pemograman I <br>
**Topik_**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;Penyeleksian

### Tujuaan

1. Dengan mengikuti perkuliahan ini mahasiswa diharapkan mampu menggunakan dan memahami pembuatan program sederhana.
2. Dengan mengikuti perkuliahan ini mahasiswa diharapkan mampu memahami konsep OOP.

### Tools

1. Personal Computer
2. IDE / Text Editor 

## Projek Kerja

### Penyeleksian kondisi **If**

Gunakan seleksi **if** untuk memeriksa apakah suatu variabel/ekspresi memenuhi persyaratan suatu kondisi. Seleksi **if** menggunakan ekspresi **boolean** untuk menentukan apakah suatu statement/blok statement akan dieksekusi atau tidak. Bila variabel/ekspresi memenuhi persyaratan kondisi, maka seleksi akan bernilai “benar”, dan kemudian statement atau blok statement yang menyertai “**if**” tersebut akan dieksekusi. <br>
Cara paling dasar untuk menguji suatu kondisi di Java adalah dengan menggunakan pernyataan if. Pernyataan if menguji apakah suatu kondisi benar atau salah dan mengambil tindakan hanya jika kondisinya benar.

### Bentuk **If..Else**

Dibutuhkan tambahan keyword **else** sebagai pelengkap **if** untuk menambahkan konsekuensi ini, sehingga disebut juga bentuk **if..else**. Sama dengan **if**, **else** juga hanya akan mengeksekusi sebanyak satu statement tang terletak persisi di bawahnya. Dibutuhkan blok setelah deklarasi **else** untuk mengeksekusi sejumlah statement. Bila terdapat beberapa kemungkinan konsekuensi (*multiple condition*), setelah suatu **if..else** kita dapat menambahkan **if..else** yang lainnya. 

### Bentuk **If** atau **If..else** bersarang (*nested if..else*)

**if** atau **if..else** itu dapat ditempatkan sebagai suatu blok seleksi di dalam blok **if** atau **if..else** yang lain. <br>
Bila pada bentuk multiple **if..else** kedudukan masing-masing **if..else** adalah sederajat, namun pada *nested*  **if..else**, kedudukannya bertingkat. Kondisi **if..else** tingkat pertama akan menyeleksi variabel/objek untuk pertama kali, bila lulus, maka variabel atau objek itu akan menghadapi seleksi **if..else** tahap kedua, bila lulus lagi ke seleksi **if..else** ketiga, dan seterusnya.

### Penyeleksian kondisi **Switch**

Selain bentuk seleksi kondisi **if**, dalam Java juga dikenal cara penyeleksian **switch**. Bentuk ini digunakan untuk menyeleksi kondisi yang memiliki banyak kemungkinan (*multiple condition*), sama seperti multiple **if..else**.

## Langkah Kerja

### Contoh program penyeleksian kondisi if

1. Buatlah sebuah project baru dengan nama **Demo If**, dengan class *DemoIf.java*.
2. Sesuaikan sourcode pada file tersebut seperti yang ada pada file [DemoIf.java](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Pertemuan%2003/Demo%20If/src/demoif/DemoIf.java "Buka di Github") berikut.
3. Jalankan program, maka hasilnya sebagai berikut:
	- Jika angka yang dimasukkan kurang dari 60
	![Output - Demo If](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2001.png "Output - Demo If #1")
	- Jika nilai yang dimasukkan sama atau lebih besar dari 60
	![Output - Demo If](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2002.png "Output - Demo If #2")

### Contoh program penyeleksian kondisi if..else atau if..else bersarang

1. Buatlah sebuah project baru dengan nama **Demo If Else**, dengan *class DemoIfElse.java*.
2. Sesuaikan sourcode pada file tersebut seperti yang ada pada file [DemoIfElse.java](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Pertemuan%2003/Demo%20If%20Else/src/demoifelse/DemoIfElse.java "Buka di Github") berikut.
3. Jalankan program, maka:
	- Jika imput yang dimasukkan kuran dari 0, atau lebih dari 100, maka akan tampil:
	![Output - Demo If Else](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2003.png "Output - Demo If Else #1")
	![Output - Demo If Else](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2004.png "Output - Demo If Else #2")
	- Jika angka yang dimasukkan diantara 0 dan 100:
	![Output - Demo If Else](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2005.png "Output - Demo If Else #3")
	![Output - Demo If Else](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2006.png "Output - Demo If Else #4")
	![Output - Demo If Else](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2007.png "Output - Demo If Else #5")
	![Output - Demo If Else](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2008.png "Output - Demo If Else #6")

### Contoh program penyeleksian kondisi switch:

1. Buatlah sebuah project baru dengan nama **Demo Switch**, dengan class *DemoSwitch.java*.
2. Sesuaikan sourcode pada file tersebut seperti yang ada pada file [DemoSwitch.java](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Pertemuan%2003/Demo%20Switch/src/demoswitch/DemoSwitch.java "Buka di Github") berikut.
3. Jalankan program tersebut, maka kemungkinan hasilnya adalah:
![Output - Demo Switch](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2009.png "Output - Demo Swich #1")
![Output - Demo Switch](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2010.png "Output - Demo Swich #2")
![Output - Demo Switch](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2011.png "Output - Demo Swich #3")

## Evaluasi dan Penugasan

Buatlah sebuah program aplikasi yang dapat menampilkan kepribadian seseorang melalui pilihan warna favorit dengan menggunakan penyeleksian kondisi switch! <br>
Contoh:
<table>
	<tr>
		<td>Merah</td>
		<td>Berani, percaya diri, teguh pendirian</td>
	</tr>
	<tr>
		<td>Pink</td>
		<td>Lemah Lembut, baik, penyayang</td>
	</tr>
	<tr>
		<td>Hijau</td>
		<td>Pencinta alam, sejuk hatinya</td>
	</tr>
	<tr>
		<td>Dll</td>
		<td></td>
	</tr>
</table>

> Buatkan untuk 8 kemungkinan pilihan warna!

- Program **Tugas - Pertemuan 3** bisa di lihat  [disini](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/tree/master/Pertemuan%2003/Tugas "Buka di Github")
- Class [Main.java](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Pertemuan%2003/Tugas/src/com/tugas/Main.java "Buka di Github")
- Outputnya : <br>
![Output - Tusgas](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2012.png "Output - Tugas #1")
![Output - Tusgas](https://github.com/Fajar-ab/Pemograman-Dasar-JAVA-SCM/blob/master/Image/%23P03%20-%2013.png "Output - Tugas #2")

> 👉 Lihat kembali penamaan **class** dan penggunaan **package** yang di pakai dalam beberapa program di atas.

