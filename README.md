# praktikum-web1
# Apa itu HTML?
HTML adalah singkatan dari Hyper Text Markup Language

HTML adalah bahasa markup standar untuk membuat halaman Web

HTML menjelaskan struktur halaman Web

HTML terdiri dari serangkaian elemen

Elemen HTML memberi tahu browser cara menampilkan konten

Elemen HTML memberi label pada bagian konten seperti "ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dll.
# Dokumen HTML sederhana:

  <!DOCTYPE html>
  
<html>
  
<head>
  
<title> Page Title </title>

</head>

<body>
  
<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>

</html>

  penjelasan:
  
Deklarasi tersebut <!DOCTYPE html>mendefinisikan bahwa dokumen ini adalah dokumen HTML5

Elemen <html>adalah elemen akar dari halaman HTML

Elemen tersebut <head>berisi informasi meta tentang halaman HTML

Elemen <title>menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman)

Elemen <body>mendefinisikan badan dokumen, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, hyperlink, tabel, daftar, dll.

Elemen <h1>mendefinisikan judul besar

Elemen <p>mendefinisikan paragraf
  
# Apa itu Elemen HTML?
Elemen HTML ditentukan oleh tag awal, beberapa konten, dan tag akhir:
< tagname > Konten ada di sini... < /tagname >

Elemen HTML adalah segalanya mulai dari tag awal hingga tag akhir:

Elemen HTML dapat disarangkan (artinya elemen dapat berisi elemen lain).

Semua dokumen HTML terdiri dari elemen HTML bersarang.

Contoh berikut berisi empat elemen HTML ( <html>, <body>, <h1> dan <p>) 

Elemennya <html>adalah elemen root dan mendefinisikan keseluruhan dokumen HTML. Ini memiliki tag awal <html>dan tag akhir </html>. Lalu, di dalam <html>elemen tersebut terdapat <body> elemen  

Elemen <body>mendefinisikan isi dokumen. Ini memiliki tag awal <body>dan tag akhir </body>.
Kemudian, di dalam <body>elemen tersebut terdapat dua elemen lainnya: <h1>dan <p> 

Elemen <h1>mendefinisikan judul. Ini memiliki tag awal <h1>dan tag akhir </h1>  

Elemen <p>mendefinisikan paragraf. Ini memiliki tag awal <p>dan tag akhir </p>  

Elemen HTML yang tidak memiliki konten disebut elemen kosong.

Tag <br>mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup 

Tag HTML tidak membedakan huruf besar dan kecil: <P>artinya sama dengan <p>.

Standar HTML tidak memerlukan tag huruf kecil, tetapi direkomendasikan huruf kecil dalam HTML
  
 # Attributes HTML:
Semua elemen HTML dapat memiliki atribut
Atribut memberikan informasi tambahan tentang elemen
Atribut selalu ditentukan dalam tag awal
Atribut biasanya datang dalam pasangan nama/nilai seperti: name="value" 
Semua elemen HTML dapat memiliki atribut
Atribut hrefmenentukan <a>URL halaman yang dituju link tersebut
Atribut srcmenentukan <img>jalur ke gambar yang akan ditampilkan
Atribut widthdan heightmemberikan <img>informasi ukuran untuk gambar
Atribut altmenyediakan <img>teks alternatif untuk sebuah gambar
Atribut styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya
Atribut langtag <html>menyatakan bahasa halaman Web
Atribut titlemendefinisikan beberapa informasi tambahan tentang suatu elemen 

# Beberapa perintah di HTML:
  - Heading HTML
Heading HTML ditentukan dengan tag <h1>to <h6>.
<h1>mendefinisikan judul yang paling penting. <h6>mendefinisikan judul yang paling tidak penting
input:
<!DOCTYPE html>
<html>
<body>
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
</body>
</html>
output:
  - Paragraf HTML
Paragraf HTML didefinisikan dengan <p>tag
input:
<!DOCTYPE html>
<html>
<body>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
</body>
</html>
output:
  - Link HTML
Link HTML ditentukan dengan <a>tag
Tujuan link ditentukan dalam hrefatribut. 
Atribut digunakan untuk memberikan informasi tambahan tentang elemen HTML.  
input:
<!DOCTYPE html>
<html>
<body>
<h2>HTML Links</h2>
<a href="https://www.w3schools.com">This is a link</a>
</body>
</html>
output:
  - gambar HTML
Gambar HTML ditentukan dengan <img>tag.
File sumber ( src), teks alternatif ( alt), width, dan heightdisediakan sebagai atribut
input:
<!DOCTYPE html>
<html>
<body>
<h2>HTML Images</h2>
<p>HTML images are defined with the img tag:</p>
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
</body>
</html>
output:
