# Lab5web
# Latihan Javascript

## ConsoleLog dan document write

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan JS</title>
</head>
<body>
    <h1>Pengenalan Java Script</h1>
    <h3>Doc write dan console log</h3>
</body>
<script>
        document.write("Hello World");
        console.log("Hello World");
</script>
</html>
```
![pict1](https://github.com/DimasF3009/Lab5web/assets/115356128/454c3835-1434-42b8-bab0-a1bc74f7e813)


## Pemakaian Alert
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan JS</title>
</head>
<body>
    <h1>Pengenalan Java Script</h1>
    <h3>Doc write dan console log</h3>
</body>
<script>
        window.alert("Halo Dimas")
</script>
</html>
```
![pict2](https://github.com/DimasF3009/Lab5web/assets/115356128/2bad3446-bdfb-4b92-af46-8635ebab830a)


## Penggunaan Method Dalam Objek
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan JS</title>
</head>
<body>
    <h1>Pengenalan Java Script</h1>
    <h3>Doc write dan console log</h3>
</body>
<script>
        document.write("Selamat Mencoba Javascript <br>");
        document.write("Semoga Sukses");
</script>
</html>
```
![pict3](https://github.com/DimasF3009/Lab5web/assets/115356128/a6aaf25f-809a-498f-86ce-ff50cf403374)


## Pemakaian Prompt
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan JS</title>
</head>
<body>
    <h1> Pengenalan Java Script</h1>
</body>
<script>
        var nama = prompt("Siapa nama anda?", "Masukan nama anda");
        document.write("hai, " + nama )
</script>
</html>
```
![Pict4](https://github.com/DimasF3009/Lab5web/assets/115356128/6cfe1bd3-5fbf-4cd5-a8b3-246467641412)

![Pict5](https://github.com/DimasF3009/Lab5web/assets/115356128/39ecb4df-aeeb-4018-b655-b93536ef6ad5)


## Membuat fungsi dan memanggilnya
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan JS</title>
</head>
<body onload= pesan()>
    <h1> Pengenalan Java Script</h1>
</body>
<script language = "javascript">
        function pesan() {
            alert ("Panggil JS")
        }
</script>
</html>
```
![pict6](https://github.com/DimasF3009/Lab5web/assets/115356128/d45be6fd-1ea2-4691-9c07-be01a74ce4c8)


## Operasi Aritmatika JS
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh program javascript</title>
</head>
<body>
    <input type="button" name="button1" value="hitung" onclick=test(10,5)>
</body>
<script language="javascript">
        function test (val1, val2)
        {
            document.write("<br>" + "perkalian = val1*val2" + "<br>")
            document.write(val1*val2)
            document.write("<br>" + "pembagian = val1:val2" + "<br>")
            document.write(val1/val2)
            document.write("<br>" + "penjumlahan = val1*val2" + "<br>")
            document.write(val1+val2)
            document.write("<br>" + "pengurangan = val1-val2" + "<br>")
            document.write(val1-val2)
            document.write("<br>" + "modulus = val1%val2" + "<br>")
            document.write(val1%val2)
        }
</script>
</html>
```
![pict7](https://github.com/DimasF3009/Lab5web/assets/115356128/4f69de16-3f96-409f-8c78-c706140a3027)


















