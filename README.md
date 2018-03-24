# Tugas-Proweb-4
## algoritma dan pseudocode
````sh
Algoritma login 3 kali salah passwoord
1.	Start
2.	Masukkan username dan password
3.	Klik tombol Login
4.	Jika user name dan password benar,maka akan masuk ke halaman selanjutnya
5.	Jika salah keluar peringatan
6.	Jika salah sebanyak 3 kali maka akan di blokir
7.	Jika tidak mengisi username atau password akan muncul dialog peringatan 
8.	End

Pseudocode
1.	Pertama buat sintak html nya untuk tampilan awal
2.	Berikan sintak php didalam index.php untuk menentukan aksi ketika salah username dan password
3.	Buat file login untuk aksi username dan password benar
        <?php
        session_start();
        $user = $_POST["inEmail"];
        $pass = $_POST["inPassword"];
        //================================
        $dbuser = "admin@gmail.com";
        $dbpass = "admin123";
        //================================
        if($user == $dbuser && $pass == $dbpass){
            ?>
            <script>
                window.location="tampilan.php";
            </script>
         <?php
4.	Panggil file login di index.php untuk sebuah aksi ketika user dan password benar
5.	Ketika benar index akan mengirim ke login.php


````
![flow](https://github.com/NabilahTm/Tugas-Proweb-4/blob/master/flowchart%20nabilah_Page-1.jpg)
![gabar1](https://github.com/NabilahTm/Tugas-Proweb-4/blob/master/gbr1%20salah%20user.PNG)
![gambar2](https://github.com/NabilahTm/Tugas-Proweb-4/blob/master/gbr2%20apabila%20password%20belum%20terisi.PNG)
![gambar3](https://github.com/NabilahTm/Tugas-Proweb-4/blob/master/gbr3%20berhasil%20login.PNG)


