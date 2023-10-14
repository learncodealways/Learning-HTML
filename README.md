# Learning-HTML
   <h1>Belajar Dasar Pemrograman Web</h1>

<h2>Paragraf</h2>
<p>Paragraf adalah elemen paling mendasar dari sebuah dokumen teks. Pada HTML, kita bisa menunjukkan sebuah paragraf dengan menggunakan elemen <p> </p>

<p>Ketika menggunakan elemen paragraf, browser akan menampilkannya dalam baris baru dan sedikit jarak (space) di bawah elemen.</p>
<b>Catatan:</b>
<p>Pastikan kita selalu gunakan elemen HTML dalam menamoilkan seluruh teks (konten) yang ada pada dokumen HTML. Teks yang ditampilkan tanpa dibungkus elemen disebut anonymus text.</p>

<hr>

<h2>Heading</h2>
<p>Kita menggunakan <b>h1</b> dan <b>h2</b> dalam mengindikasi judul dan subjudul pada kontennya, adal elemen <b>h1</b> hingga <b>h6</b> elemen heading yang dapat digunakan, standar heading ditampilkan dalam tulisa <b>tebal</b> (bolded text), dimulai dari <b>h1</b> dengan urutan teks paling besar kemudia berurutan sesuai dengan level headingnya.</p>

<hr>

<h2>List</h2>
<p>Sebagaimana yang sudah disebutkan pada pembahasan paragraf, tidak semua teks dibungkus oleh paragraf, salah satunya list. Kita pun terbiasa membuat list dalam kehidupan sehari-hari, baik membuat to-do list maupun daftar yang terstruktur sekalipun. </p>

<p>Pada HTML terdapat tiga tipe list.</p>

<ol>
  <li>Unordered lists: daftar yang ditampilkan tidak memiliki urutan. </li>
  <li>Ordered lists: daftar yang ditampilkan secara terurut.</li>
  <li>Description lists: daftar yang terbuat dari beberapa istilah diikuti dengan deskripsi dari istilah tersebut.</li>
</ol>

<h4>Unordered List</h4>
<p>Seperti namanya, unordered list merupakan daftar yang tidak mementingkan urutan. Standarnya, unordered list menampilkan bullet pada tiap item list-nya (tetapi kita bisa mengubahnya dengan styling).

Untuk menetapkan konten sebagai unordered list kita gunakan <ul></ul> kemudian di dalam elemen tersebut kita gunakan tags <li></li> untuk menetapkan item pada list tersebut. Di antara tag elemen <li>, kita dapat mengisikan konten apa pun termasuk elemen HTML lain. Contohnya, kita dapat memasukkan sebuah heading atau paragraf pada item.</p>

<h4>Ordered List</h4>
<p>Ordered list digunakan untuk membuat list yang mementingkan urutan. Contohnya, membuat daftar instruksi langkah demi langkah sehingga dibutuhkan urutan yang sesuai. Ordered list bekerja seperti unordered list, tetapi perbedaannya adalah pada tiap item menampilkan angka bukan sebuah bullet. Angka yang ditampilkan, otomatis berurut tiap item-nya sehingga kita tidak perlu menuliskan secara kasar urutan nomornya. Hal ini tentu mempermudah kita untuk mengorganisasi tiap itemnya. Untuk menetapkan konten sebagai ordered list kita gunakan <ol></ol>. Sama seperti unordered list, tiap item dalam list ditetapkan dengan menggunakan tags <li></li>.</p>

<p>Pada ordered list, tipe urutan angkanya dapat kita atur melalui sebuah atribut type. Contohnya, selain nomor, urutan angka dapat diganti dengan alfabet ataupun angka romawi.</p>

<table border="1" cellspacing="0" cellpadding="10">

<thead>
<tr>
    <th colspan="2">Nilai</th>  
    <th colspan="4">Deskripsi</th>  
</tr>
</thead>

<tbody>
<tr>
<td>1</td> 
</tr>

<tr>
<td>a</td>
</tr>

<tr>
<td>A</td>
</tr>

<tr>
<td>i</td></tr>
<tr>
<td>I</td>
</tr>
</tbody>

<tbody>

 
  <tr><td>Menggunakan angka dalam urutan item (default).</td>
  <td>Menggunakan huruf kecil dalam urutan item.</td> 
<td>Menggunakan huruf besar dalam urutan item.</td> 
 <td>Menggunakan huruf romawi kecil dalam urutan item.</td> 
  <td>Menggunakan huruf romawi besar dalam urutan item.</td> 
  </tr>
</tbody>



 <tfoot>
<tr>
    <th colspan="2">Nilai</th>  
    <th colspan="4">Deskripsi</th>  
</tr>
 </tfoot>


</table>









