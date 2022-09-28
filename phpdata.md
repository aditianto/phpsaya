<?php

$Nama = "Aditianto";
$Nim = "202520013";
$Alamat = "Kedung Pomahan Wetan, Kemiri";
$Email = "iantoadit@gmail.com";
$Minat = "Editing";
?>
<h1 style="text-align: center;">Data Saya</h1>
<table style="background-color: yellow;">
<tr style="background-color: green;">
<td><?php echo "Nim";?>
<td><?php echo ":"; ?></td>
<td><?php echo $Nim ?></td>
<td rowspan="7">
<img src="gambar.jpeg" width="300" height="200">
</td>
</tr>
<tr style="background-color: green;">
<td><?php echo "Nama "; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Nama ;?></td>
</tr>
<tr style="background-color: green;">
<td><?php echo "Alamat"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Alamat ;?></td>
</tr>
<tr style="background-color: green;">
<td><?php echo "E-Mail"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Email ;?></td>
</tr>
<tr style="background-color: green;">
<td><?php echo "Bidang Minat"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Minat ;?></td>
</tr>
</table>
