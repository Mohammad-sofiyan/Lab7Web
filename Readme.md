## Nama    : Mohammad Sofiyan 
## kelas   : TI20.A2
## Matkul  : Pemrograman web


## langkah pertama 
![instal_xampp](img/xampp.png)
Menginstal xampp

## langkah kedua 
![menjalankan_xampp](img/xampp2.png)
Menjalankan xampp 

## langkah ketiga 
![memulai_php](img/folder_php.png)
Memulai php pada folder

![localhost](img/localhost.png)
Membuka Localhost

## langkah keepat
![pariabel](img/pariabel_php.png)
Pariabel pada php
```php
<?php
echo "Hello World";
?>
```
## langkah kelima
![pariabelS](img/pariabelS.png)
Memanggil paraibel
```php
<?php
$nim = "0411500400";
$nama = 'Abdullah';
echo "NIM : " . $nim . "<br>";
echo "Nama : $nama";
?>
```
## langkah keenam
![preadenfine_variable](img/Preadefine_variable.png)
deklarasi preadenfine variable
```php
<?php
echo 'Selamat Datang ' . $_GET['nama'];
?>
```
## langkah ketujuh
![from_input](img/from_Input.png)
Membuat form input
```php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>php dasar</title>
</head>
<body>
<h2>Form Input</h2>
<form method="post">
<label>Nama: </label>
<input type="text" name="nama">
<input type="submit" value="Kirim">
</form>
<?php
echo 'Selamat Datang ' . $_POST['nama'];
?>
</body>
</html>
```
## langkah kedelapan
![oprator](img/oprator.png)
oprator pada php
```php
<?php
$gaji = 1000000;
$pajak = 0.1;
$thp = $gaji - ($gaji*$pajak);
echo "Gaji sebelum pajak = Rp. $gaji <br>";
echo "Gaji yang dibawa pulang = Rp. $thp";
?>
```
## langkah kesembilan 
![kondisi_if](img/kondisi_IF.png)
Kondisi IF else pada perogram php
```php
<?php
$nama_hari = date("l");
if ($nama_hari == "Sunday") {
echo "Minggu";
} elseif ($nama_hari == "Monday") {
echo "Senin";
} else {
echo "Selasa";
}
?>
```
## langkah kesepuluh
![kondisi_swit](img/kondisi_swit.png)
kondisi swit pada perogram php
```php
<?php
$nama_hari = date("l");
switch ($nama_hari) {
case "Sunday":
echo "Minggu";
break;
case "Monday":
echo "Senin";
break;  
case "Tuesday":
    echo "Selasa";
    break;
    default:
    echo "Sabtu";
}
    ?>
```
## langkah kesebelas 
![perulangan_for](img/perulangan_for.png)
perulangan for pada php
```php
<?php
echo "Perulangan 1 sampai 10 <br />";
for ($i=1; $i<=10; $i++) {
echo "Perulangan ke: " . $i . '<br />';
}
echo "Perulangan Menurun dari 10 ke 1 <br />";
for ($i=10; $i>=1; $i--) {
echo "Perulangan ke: " . $i . '<br />';
}
?>
```
## langkan keduabelas 
![perulangan_while](img/perulangan_while.png)
pengulangan while pada php
```php
<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
while ($i<=10) {
echo "Perulangan ke: " . $i . '<br />';
$i++;
}
?>
```
## langkah ketigabelas
![perulangan_douwhile](img/perulangan_douwhile.png)
perulangan dowhile pada php 
```php 
<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
do {
echo "Perulangan ke: " . $i . '<br />';
$i++;
} while ($i<=10);
?>
```