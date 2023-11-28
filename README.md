# php requiare
![image](https://github.com/heyytayo963/Lab9web/blob/main/IMG-20231128-WA0043.jpg)
- header.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen' />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">home</a>
            <a href="tentang.php">tentang</a>
            <a href="kontak.php">kontak</a>
        </nav>
```
- footer.php
```
<footer>
            <p>&copy; 2021, informatika, universitas pelita bangsa</p>
        </footer>
    </div>
</body>
</html>
```
- home.php
```
<?php require('header.php'); ?>

<div class="content">
    <h2>ini halaman About</h2>
    <p>ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
- about.php
```
<?php require('header.php'); ?>
<div class="content">
    <h2>ini halaman home</h2>
    <p>ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

