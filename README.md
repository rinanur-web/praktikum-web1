# praktikum-web1
# Apa itu HTML?
HTML adalah singkatan dari Hyper Text Markup Language

HTML adalah bahasa markup standar untuk membuat halaman Web

HTML menjelaskan struktur halaman Web

HTML terdiri dari serangkaian elemen

Elemen HTML memberi tahu browser cara menampilkan konten

Elemen HTML memberi label pada bagian konten seperti "ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dll.

penjelasan:
  
Deklarasi tersebut !DOCTYPE html mendefinisikan bahwa dokumen ini adalah dokumen HTML5

Elemen html adalah elemen akar dari halaman HTML

Elemen tersebut head berisi informasi meta tentang halaman HTML

Elemen title menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman)

Elemen body mendefinisikan badan dokumen, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, hyperlink, tabel, daftar, dll.

Elemen h1 mendefinisikan judul besar

Elemen p mendefinisikan paragraf
  
# Apa itu Elemen HTML?
Elemen HTML ditentukan oleh tag awal, beberapa konten, dan tag akhir.Elemen HTML adalah segalanya mulai dari tag awal hingga tag akhir. Elemen HTML dapat disarangkan (artinya elemen dapat berisi elemen lain). Semua dokumen HTML terdiri dari elemen HTML bersarang.

Contoh berikut berisi empat elemen HTML ( html, body, h1 dan p) 

Elemen html adalah elemen root dan mendefinisikan keseluruhan dokumen HTML. 

Ini memiliki tag awal html dan tag akhir /html. Lalu, di dalam html elemen tersebut terdapat body elemen.

Elemen body mendefinisikan isi dokumen. Ini memiliki tag awal body dan tag akhir /body.

Kemudian, di dalam body elemen tersebut terdapat dua elemen lainnya: h1 dan p. 

Elemen h1 mendefinisikan judul. Ini memiliki tag awal h1 dan tag akhir /h1. Elemen p mendefinisikan paragraf. 

Ini memiliki tag awal p dan tag akhir /p.  

Elemen HTML yang tidak memiliki konten disebut elemen kosong.

Tag br mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup.

Tag HTML tidak membedakan huruf besar dan kecil: P artinya sama dengan p.

Standar HTML tidak memerlukan tag huruf kecil, tetapi direkomendasikan huruf kecil dalam HTML
  
 # Attributes HTML:
Semua elemen HTML dapat memiliki atribut. Atribut memberikan informasi tambahan tentang elemen.Atribut selalu ditentukan dalam tag awal. Atribut biasanya datang dalam pasangan nama/nilai seperti: name="value" . Semua elemen HTML dapat memiliki atribut.
Atribut href menentukan a, URL halaman yang dituju link tersebut

Atribut src menentukan img, jalur ke gambar yang akan ditampilkan

Atribut width dan height memberikan img, informasi ukuran untuk gambar

Atribut alt menyediakan img, teks alternatif untuk sebuah gambar

Atribut style digunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya
Atribut lang tag html, menyatakan bahasa halaman Web

Atribut title mendefinisikan beberapa informasi tambahan tentang suatu elemen 

# Beberapa perintah di HTML:
  * Heading HTML
Heading HTML ditentukan dengan tag h1 to h6. h1 mendefinisikan judul yang paling penting. h6 mendefinisikan judul yang paling tidak penting

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20122749.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20122700.png?raw=true)
  * Paragraf HTML
Paragraf HTML didefinisikan dengan <p>tag

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20122904.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20122843.png?raw=true)

  * Link HTML
Link HTML ditentukan dengan a tag. Tujuan link ditentukan dalam href atribut.
 
Atribut digunakan untuk memberikan informasi tambahan tentang elemen HTML. 

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20122959.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20122946.png?raw=true)

  * gambar HTML
    
Gambar HTML ditentukan dengan img tag. File sumber ( src), teks alternatif ( alt), width, dan heightdisediakan sebagai atribut

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20123121.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20123041.png?raw=true)

  * Table HTML
    
![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20123353.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20123319.png?raw=true)

* blokquote HTML

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20123522.png?raw=true)

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20123505.png?raw=true)

# Apa itu CSS
CSS adalah singkatan dari Cascading Style Sheet

CSS menjelaskan bagaimana elemen HTML ditampilkan di layar, kertas, atau di media lain

CSS menghemat banyak pekerjaan. Itu dapat mengontrol tata letak beberapa halaman web sekaligus

Stylesheet eksternal disimpan dalam file CSS

CSS digunakan untuk menentukan gaya halaman web Anda, termasuk desain, tata letak, dan variasi tampilan untuk berbagai perangkat dan ukuran layar.

# sintaks CSS:

selector menunjuk ke elemen HTML yang ingin Anda gaya.

Blok deklarasi berisi satu atau lebih deklarasi yang dipisahkan oleh titik koma.

Setiap deklarasi menyertakan nama properti CSS dan nilainya, dipisahkan oleh titik dua.

Beberapa deklarasi CSS dipisahkan dengan titik koma, dan blok deklarasi diapit oleh kurung kurawal.

contohnya:

p{
  color: red;
  text-align: center;
  }

penjelasan:

p adalah selector dalam CSS (menunjuk ke elemen HTML yang ingin Anda gaya: p ).

color adalah properti, dan red merupakan nilai properti

text-align adalah properti, dan center merupakan nilai properti

# ID selector

selector ID CSS

selector id menggunakan atribut id dari elemen HTML untuk memilih elemen tertentu.

Id suatu elemen bersifat unik dalam suatu halaman, sehingga pemilih id digunakan untuk memilih satu elemen unik!

Untuk memilih elemen dengan id tertentu, tulis karakter hash (#), diikuti dengan id elemen tersebut.

Contoh:

#para1 {
  text-align: center;
  color: red;
}

# Class selector

selector class CSS

selector class memilih elemen HTML dengan atribut kelas tertentu.

Untuk memilih elemen dengan kelas tertentu, tuliskan karakter titik (.), diikuti dengan nama kelas.

 contoh:

 .center {
  text-align: center;
  color: red;
}

# Universal selector

selector Universal CSS

selector universal (*) memilih semua elemen HTML pada halaman.

contoh:

* *{
  text-align: center;
  color: blue;
}

# Grouping selector

Grouping selector CSS

 grouping selector memilih semua elemen HTML dengan definisi gaya yang sama.

Lihatlah kode CSS berikut (elemen h1, h2, dan p memiliki definisi gaya yang sama)

contoh:

h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

# Tiga Cara Memasukkan CSS
Ada tiga cara menyisipkan style sheet:

CSS eksternal

CSS Internal

CSS Inline

# CSS eksternal
Dengan style sheet eksternal, Anda dapat mengubah tampilan seluruh situs web hanya dengan mengubah satu file!

Setiap halaman HTML harus menyertakan referensi ke file style sheet eksternal di dalam elemen <link>, di dalam bagian head.

Style sheet eksternal dapat ditulis dalam editor teks apa pun, dan harus disimpan dengan ekstensi .css.

File .css eksternal tidak boleh berisi tag HTML apa pun.

Berikut tampilan file "mystyle.css"

# CSS Internal
Lembar gaya internal dapat digunakan jika satu halaman HTML memiliki gaya yang unik.

Gaya internal didefinisikan di dalam elemen <style>, di dalam bagian head.

# CSS Inline
Gaya inline dapat digunakan untuk menerapkan gaya unik pada satu elemen.

perintah di CSS:

* List

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124252.png?raw=true)

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124322.png?raw=true)

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124227.png?raw=true)

  * Letter Spacing
 
    ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124411.png?raw=true)

    ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124353.png?raw=true)

    * Box Model
   
      ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124457.png?raw=true)

      ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124444.png?raw=true)

      * Border Style
     
        ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124539.png?raw=true)

        ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124554.png?raw=true)

        ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124524.png?raw=text)

        * Table Hover
       
          ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124654.png?raw=true)

          ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124705.png?raw=true)

          ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124638.png?raw=true)

          * Text Color
         
            ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124743.png?raw=true)

            ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124729.png?raw=true)

# Apa itu JAVASCRIPT

JavaScript adalah bahasa pemrograman yang digunakan dalam pengembangan website agar lebih dinamis dan interaktif. JavaScript dapat meningkatkan fungsionalitas pada halaman web. Bahkan dengan JavaScript ini kamu bisa membuat aplikasi, tools, atau bahkan game pada web.

Untuk menggunakan gaya sebaris, tambahkan atribut style ke elemen yang relevan. Atribut style dapat berisi properti CSS apa pun.

# Variable javascript
Dalam bahasa pemrograman, variabel digunakan untuk menyimpan nilai data.

JavaScript menggunakan kata kunci var, letdan constuntuk mendeklarasikan variabel.

Tanda sama dengan digunakan untuk memberikan nilai pada variabel.

variabel adalah Wadah untuk Menyimpan Data
Variabel JavaScript dapat dideklarasikan dengan 4 cara:

Secara otomatis

Menggunakan var
<script>
var x = 5;
var y = 6;
var z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124920.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124910.png?raw=true)

Menggunakan let
<script>
let x = 5;
let y = 6;
let z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124850.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124838.png?raw=true)

Menggunakan const
<script>
const x = 5;
const y = 6;
const z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124951.png?raw=true)

![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20124938.png?raw=true)

# Pengidentifikasi / Nama JavaScript
Pengidentifikasi adalah nama JavaScript.

Pengidentifikasi digunakan untuk memberi nama variabel dan kata kunci, serta fungsi. Aturan untuk nama resmi sama di sebagian besar bahasa pemrograman.

Nama JavaScript harus dimulai dengan:

Sebuah huruf (AZ atau az)

Tanda dolar ($)

Atau garis bawah (_)

Karakter berikutnya dapat berupa huruf, angka, garis bawah, atau tanda dolar.

Semua variabel JavaScript harus diidentifikasi dengan nama unik .Nama-nama unik ini disebut pengidentifikasi .Pengidentifikasi dapat berupa nama pendek (seperti x dan y) atau nama yang lebih deskriptif (usia, jumlah, totalVolume).

Aturan umum untuk membuat nama variabel (pengidentifikasi unik) adalah:

Nama dapat berisi huruf, angka, garis bawah, dan tanda dolar.

Nama harus diawali dengan huruf.

Nama juga bisa diawali dengan $ dan _ (tetapi kami tidak akan menggunakannya dalam tutorial ini).

Nama peka huruf besar-kecil (y dan Y adalah variabel berbeda).

Kata-kata khusus (seperti kata kunci JavaScript) tidak dapat digunakan sebagai nama.

javaScript peka huruf besar-kecil. Semua pengidentifikasi JavaScript peka huruf besar-kecil . Variabel lastNamedan lastname, adalah dua variabel yang berbeda.

JavaScript menggunakan kumpulan karakter Unicode . Unicode mencakup (hampir) semua karakter, tanda baca, dan simbol di dunia.

# Tipe Data JavaScript
Variabel JavaScript dapat menampung angka seperti 100 dan nilai teks seperti "John Doe". Dalam pemrograman, nilai teks disebut string teks.

JavaScript dapat menangani banyak tipe data, tetapi untuk saat ini, angka dan string. String ditulis di dalam tanda kutip ganda atau tunggal. Angka ditulis tanpa tanda petik. Jika Anda memasukkan angka dalam tanda kutip, angka tersebut akan diperlakukan sebagai string teks.

# arithmetic javascript

* Tambah

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125438.png?raw=true)

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125424.png?raw=true)

  * Kurang

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125533.png?raw=true)

  ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125506.png?raw=true)

  * Kali
 
    ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125622.png?raw=true)

    ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125555.png?raw=text)

    * Bagi
   
      ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125653.png?raw=text)

      ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125643.png?raw=text)

      * Modulus
     
        ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125724.png?raw=true)

        ![alt text](https://github.com/rinanur-web/praktikum-web1/blob/main/gambar/Screenshot%202024-04-05%20125712.png?raw=true)
