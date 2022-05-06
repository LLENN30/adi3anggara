# adi3anggara
html
<!DOCTYPE l>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compaible" content="ie=edge">
        <title>adi 3 anggara</title>
    </head>
    <body>
        <!--PARAGRAF
        <p></p>=untuk membuat paragraf
        <br>=untuk membuat garis baru
        <hr>=untuk membuat garis horizontal
        <b></b>=untuk membuat cetak tebal
        <i></i>=untuk membuat cetak miring
        <u></u>=untuk membuat garis bawah
        <strong></strong>=untuk paragraf penting cetak tebal
        <em></em>=untuk paragraf penting cetak miring -->

        <!-- HEADING<h1></h1>,<h2></h2>,<h3></H3>,<h4></h4>,<h5></h5>,<h6></h6>=untuk memilih ukuran font-->

        <!--LIST
         <ol></ol>=untuk membuat list terutut
         <ul></ul>=untuk membuat list tidak terutut
         <dl></dl>=untuk membuat daftar teminologi dan definisi -->

        <!--HYPER LINK
         <a></a>=untuk menghubungkan ke website
         <a target="_self,_blank,_parent,_top"></a>
         _self untuk membuka link didalam yg sama
         _blank untuk membuka link tab baru yg baru
         id=untuk penanda-->

        <!--IMAGE
         <img src=""></img>= gambarnya ngambil dari mana
         <img src="" alt=""></img>=berguna untuk memberikan alternatif
         <img src="" title=""></img>=untuk memberikan judul pada gambar
         <img src="" width=""></img>=berguna untuk mengatur lebar gambar
         <img src="" height=""></img>=berguna untuk mengatur tinggi gambar
         width="100"=ukuran pixel width="100"ukuran halaman
         <img src="unpas.png" alt="web programing adi" width="200"></img> -->

        <!--HYPER LINK + IMAGE
         <a href="https://www.facebook.com/adi.anggara.7946">
             <img src="logo.png"
         </a>
         jika gambar nya di klik akan menuju link tersebut-->

        <!--TABLE
         <table border="1" cellspacing="0" cellspadding="5">
          <tr>=table row(baris)
              <td></td>=table data(kolom)
          </tr>
        
          <table border="1" cellspacing="0" cellspadding="5">
         <tr>
           <td rowspan="3">rowspan 3</td>
           <td colspan="2">colspan 2</td>
         </tr>
         <tr>
           <td>2,3</td>
           <td>2,3</td>
         </tr>
         <tr>
           <td>3,2</td>
           <td>3,3</td>
         </tr>
        </table>
          border=digunakan untuk menambahkan garis disekitar sel
          cellspacing=untuk menambah jarak antar sel
          cellpadding=untuk memberi luas antar sel
          colspan=untuk menggabungkan dua buah sel horizontal/kolom
          rowspan=untuk menggabungkan dua buah sel vertikal/baris-->

        <!--FORM
        <from></from>
        <input type=""></input>
        input=untuk user menginputkan sesuatu
        textarea=untuk mengisi emai, dll
        select=untuk membuat dropdown/pilihan kebawah
        button=tombol untuk mengirimkan data
        label=untuk menandai elemen input
         -->

        <P>selamat datang <br> di web adi</P>
        <br>
         <P><b><i><u>selamat datang didunia saya</u></I></b></P>
        <br>
        <P><strong>pengumuman</strong></P>web ini hanya bisa diakses oleh penting <em><u>saya sendiri</u></em>
         <hr>
        <h1>judul teks</h1>
        <P>isi artikel</P>
        <h2>sub judul</h2>
        <P>sub body artikel</P>
        <hr>

        <h3>To Do List</h3>
        <ol>
            <li>bangun tidur</li>
            <li>sarapan</li>
            <li>tidur lagi</li>
        </ol>
<!-- jika tidak ingin menggunakan urutan angka kita bisa mengubahnya menjadi <ol type="1,A,a,I,i"><ol> contoh dibawah-->
    <h3>To Do List</h3>
    <ol type="A">
        <li>bangun tidur</li>
        <li>sarapan</li>
        <li>tidur lagi</li>
    </ol>
    <hr>

    <h3>saat saya sarapan saya makan</h3>
    <ul>
        <li>nasi goreng</li>
        <li>mie goreng</li>
        <li>telur goreng</li>
    </ul>
<!-- jika kita tidak ingin menggunakan titik bulet kita bisa mengubahnya menjadi <ul type="disc,square,cicle"
</ul> contoh dibawahnya-->
    <h3>saat saya sarapan saya makan</h3>
    <ul type="cicle">
        <li>nasi goreng</li>
        <li>mie goreng</li>
        <li>telur goreng</li>
    </ul>
    <hr>

    <h3>pemrograman web</h3>
    <dl>
        <dt><strong>HTML</strong></dt>
        <dd>Hypertext Markup Language</dd>
        <dt><strong>CSS</strong></dt>
        <dd>Cascading Style Sheer</dd>
    </dl>
    <hr>
    
    <P>klik <a href="https://www.facebook.com/adi.anggara.7945">
    disini</a> untuk info selanjutnya</P>

    <p>klik <a href="halaman 2.html" target="_blank">disini</a>untuk halaman 2</p>

    <p>klik <a href="halaman 3.html">disini</a> untuk halaman 3</p>

    <P>klik <a href="halaman 3.html#bagian3">disini</a>untuk halaman 3 bagian 3</P>
    <hr>

     <img src="https://www.pngegg.com/id/png-eirrw.png">
     <hr>

     <table border="1" cellspacing="0" cellpadding="5">
         <tr>
             <td>baris 1,kolom 1</td>
             <td>baris 1,kolom 2</td>
         </tr>
         <tr>
             <td>baris 2,kolom 1</td>
             <td>baris 2,kolom 2</td>
         </tr>
     </table>
     <hr>

     <table border="1" cellspacing="0" cellpadding="5">
         <tr>
             <td>1,1</td>
             <td>1,2</td>
             <td>1,3</td>
             <td>1,4</td>
         </tr>
         <tr>
             <td>2,1</td>
             <td rowspan="2" colspan="2"></td>
             <td>2,4</td>
         </tr>
         <tr>
             <td>3,1</td>
             <td>3,4</td>
         </tr>
         <tr>
             <td>4,1</td>
             <td>4,2</td>
             <td>4,3</td>
             <td>4,4</td>
         </tr>
     </table>
     <hr>

     <form>
         <label for="username">username :</label>
         <input type="text" id=username ></input>
            <br>
         <label for="password">password :</label>
         <input type="password" id=password></input>
            <br>
         <input type="radio" id=pria name="jeniskelamin"><label for="pria">pria</label>
         <input type="radio" id=wanita name="jeniskelamin"><label for="wanita">wanita</label>
            <br>
         <input type="checkbox" id="menyanyi"><label for="menyayi">menyanyi</label>
         <input type="checkbox" id="olahraga"><label for="olahraga">olahraga</label>
         <input type="checkbox" id="ngoding"><label for="ngoding">ngoding</label>
            <br>
        <button type="submit">kirim!</button>
     </form>
    </body>
</html>
