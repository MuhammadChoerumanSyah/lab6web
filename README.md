# lab6web

## Nama : Muhammad Choeruman Syah ##
## Kelas : TI. 20. A. 1##
## NIM : 312010031 ##

# Langkah langkah praktikum 6

## 1. buat folder baru dengan nam lab6_css_framework, Buat file baru dokumen html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab6_css_framework</title>
    <link rel="stylesheet" href="https:cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
</head>
<body>
    
</body>
</html>

## 2. Buatlah layout web sederhana menggunakan css framword (Twitter Bootstrap)

# 1. Quick strat
buka web https://getbootstrap.com disini saya memakai Bootstrap 4. Copy atau download CSS & JS Bootstrap, Saya memilih copy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab6_css_framework</title>
    <link rel="stylesheet" href="https:cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
</head>
<body>
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH01sSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-fQybjgWLrvvRgtW6bF1B7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF" crossorigin="anonymous"></script>
    
    
</body>
</html>

# 2. Navbar
Buat komponen website website yang berupa menu. yang biasanya diletakkan pada header website.

untuk mencari component klik menu documentation pada web bootstrap
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Artikel</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link">Kontak</a>
                </li>
            </ul>
        </div>
    </nav>

[img](gambarlab6/gambarlab6.2.png)
[img](gambarlab6/gambarlab6.1.png)



# 3. Jumbotron
Selanjutnya buat jumbotron atau area besar pada Bootstrap, umumnya digunakan untuk menampilkan sebuah infromasi penting.
[img](gambarlab6/gambarlab6.3.png)
[img](gambarlab6/gambarlab6.4.png)

# 4. Cards
Untuk membuat body konten, menggunakan cards.

membagi kolom menggunakan display flex agar dapat memuat 2 kolom yang nanti akan di isi oleh menu List Group
[img](gambarlab6/gambarlab6.6.png)

Penjelasan :
col memberi style sebuah table berdasarkan kolom tertentu

img-rounded-circle untuk membuat border pada gambar menjadi bulat

pt-3 padding top = 3

mt-3 margin top = 3

menambah style untuk mengatur ukuran dan posisi pada gambar

[img](gambarlab6/gambarlab6.5.png)

[img](gambarlab6/gambarlab6.7.png)

# 5. List Group
Lalu tambahkan widget disamping kanan cards

[img](gambarlab6/gambarlab6.9.png)
[img](gambarlab6/gambarlab6.8.png)

# 6. Cards 2
Buat body konten untuk yang kedua, dan masih menggunakan card
[img](gambarlab6/gambarlab6.10.png)
[img](gambarlab6/gambarlab6.11.png)

# Footer
bagian akhir tambahkan footer.
[img](gambarlab6/gambarlab6.12.png)
[img](gambarlab6/gambarlab6.13.png)
[img](gambarlab6/gambarlab6.14.png)

# Tampilan Full
[img](gambarlab6/gambarlab6.15.png)
## Alhamdulillah





