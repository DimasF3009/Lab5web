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
### Hasil
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
### Hasil
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
### Hasil
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
### Hasil
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
### Hasil
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
### Hasil
![pict7](https://github.com/DimasF3009/Lab5web/assets/115356128/4f69de16-3f96-409f-8c78-c706140a3027)


## Pengkondisian JS (If else)
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belajar JS</title>
</head>
<body>
    <h1>BELAJAR JS</h1>
</body>
<script>
    var nilai = prompt("masukan nilai (0-100): ");
    var hasil = " ";
    if (nilai >= 75)
        hasil = "lulus";
    else
        hasil="gagal";
document.write("KKM 75<br>");
document.write("hasil : ",nilai," ", hasil);
</script>
</html>
```
### Hasil
![pict8](https://github.com/DimasF3009/Lab5web/assets/115356128/4fea0890-8122-4193-b7b8-4eb23abf5332)

![pict9](https://github.com/DimasF3009/Lab5web/assets/115356128/99295466-b1aa-487a-80db-474fdbda79c6)


## Penggunaan operator switch untuk seleksi kondisi
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan js</title>
</head>
<body>
    <input type="button" name="button1" value="Switch" onclick="test()">

</body>
<script>
    function test(){
        vall = window.prompt("input nilai (1-5):")
        switch(vall){
            case "1":
                document.write("Bilangan satu")
                break
            case "2":
                document.write("Bilangan dua")
                break
            case "3":
                document.write("Bilangan tiga")
                break
            case "4":
                document.write("Bilangan empat")
                break
            case "5":
                document.write("Bilangan lima")
                break
            default:
            document.write("bilangan lainya")
        }
    }
</script>
</html>
```
### Hasil
![collage](https://github.com/DimasF3009/Lab5web/assets/115356128/e3ab2a88-dff4-4ab8-8400-b17892521460)

## Form Input
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan js</title>
</head>
<body>
    <form method="post" name="kirim">
        <p>BIL <input type="text" name="T1" size="20"></p>
        <p>Merupakan BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" name="B1" value="Tebak" onclick="test()" ></p>
    </form>
</body>
<script>
    function test(){
        var val1=document.kirim.T1.value
        if(val1 %2==0)
            document.kirim.T2.value="Genap"
        else
            document.kirim.T2.value="Ganjil"
    }
</script>
</html>
```
### Hasil
<img width="393" alt="Screenshot 2023-10-28 163208" src="https://github.com/DimasF3009/Lab5web/assets/115356128/0b6ec428-f448-4e7d-ac84-c58b6a129163">

## Form Button
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan js</title>
</head>
<body>
    <form>
        <input type="button" value="Hijau" onclick="back('green')">
        <input type="button" value="putih" onclick="back('white')">
        <input type="button" value="teks kuning" onclick="teks('yellow')">
        <input type="button" value="teks biru" onclick="teks('blue')">
 
    </form>
</body>
<script>
    function back(warna){
        document.bgColor = warna;
    }
    function teks(warna){
        document.fgColor = warna;
    }
    document.write("Dimodifikasi terakhir pada"+document.lastModified)
</script>
</html>
```
### Hasil
<img width="457" alt="Screenshot 2023-10-28 164435" src="https://github.com/DimasF3009/Lab5web/assets/115356128/eded1e89-1a8b-4438-8795-ab6a6330fe75">

## DOM Menggunakan Check Box
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daftar Menu</title>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="Menu1" onclick="hitung(this) ;"/>Ayam Goreng Rp. 5.000</label><br />
    <label><input type="checkbox" value="500" id="Menu2" onclick="hitung(this) ;" />Tempe Goreng Rp. 500</label><br />
    <label><input type="checkbox" value="2500" id="Menu3" onclick="hitung(this) ;" />Telur Dadar Rp. 2.500</label><hr />
    <strong>Total Bayar : Rp.<input id="total" type="text" /></strong>
</body>
<script>
    function hitung(ele) {
        var total = document.getElementById("total").value;
            total = (total ? parseInt(total):0);
        var harga = 0;

        if (ele.checked) {
            harga = ele.value;
            total += parseInt(harga);
        } 
        else {
            harga = ele.value;
            if(total > 0)
                total -= parseInt(harga);
        }
        document.getElementById("total").value = total;
    }
</script>
</html>
```

### Hasil
![pict12](https://github.com/DimasF3009/Lab5web/assets/115356128/5ff952b8-5158-4a97-a8db-f73de82895b5)
















