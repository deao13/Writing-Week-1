**Senin, 19 September 2022**

### Unix Command Line, Git & Github Dasar

#### Unix Command Line
Mekanisme interaksi dengan sistem operasi atau perangkat lunak komputer dengan mengetikkan perintah untuk menjalankan tugas tertentu. Shell ini adalah program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi. Selain command line, kita juga punya shell berbasis grafis yang lebih dikenal dengan nama GUI atau graphical user interface.

1. Shell adalah program yang digunakan untuk memerintah sistem
2. Command Line Interface adalah jenis shell yang berbasis teks
3. Terminal Emulator adalah aplikasi untuk mengakses CLI

Contoh CLI :
   - sh
   - bash
   - zsh
   - cmd.exe

Contoh GUI :
  - Microsoft Windows
  - macOS
  - Ubuntu. 

#### Navigasi menggunakan CLI

**1. Filesystem**
Sebuah filesystem mengatur bagaimana data disimpan di dalam sebuah system. Sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree. 
  - File System Tree: Cara sistem operasi menyusun file-filenya dalam bentuk hierarki atau tree
  - Direktori yang paling atas atau paling pertama disebut “root directory”.
  - Pada Unix-Like terdapat hanya satu tree, sedangkan pada Windows terdiri dari beberapa tree

**2. Command untuk navigasi**
  1. pwd (Print Working Directory) : Command untuk current working directory
  `[email protected]:~$ /bin/pwd
  /var/www/html`

  2. ls (lists) : Command untuk melihat isi file yang ada disebuah direktori
  `$ ls /root`

  3. cd (directory) : Command untuk berpindah directory
  `cd /home/username/Downloads`

#### Manipulasi Files dan Directory

- **Membuat file dan directory**
  1. touch : Command untuk membuat suatu file
  `touch file_name.txt`
  2. mkdir : Command untuk membuat suatu directori
  `mkdir folderku`
- **Melihat isi files**
  1. head : Command untuk melihat beberapa line awal dari sebuah file text
  2. tail : Command untuk melihat beberapa line awal dari sebuah file text
  3. cat : Command untuk melihat isi sebuah file
- **Menyalin, memindahkan, dan menghapus files & directory**
  1. cp : Command untuk mengcopy files atau directory
  `cp /etc/file1.txt`
  2. mv (move) : Command untuk memindahkan files atau directory. Bisa digunakan untuk rename.
  `mv file.txt /home/username/Documents`
  3. rm (remove) : Command untuk menghapus file atau directory
  `rm filename1 filename2 filename3`

- **GIT**
  Sebuah version control system yang telah digunakan oleh para developer untuk dapat mengembangkan software secara bersamaan.
- **GitHub** 
  Sebuah website dan layanan berbasis cloud bagi para developer untuk menyimpan dan mengelola kode, serta mendokumentasikan dan mengontrol perubahannya.



**Selasa, 20 September 2022**

### HTML

- HTML atau Hypertext Markup Language adalah suatu bahasa yang menggunakan tanda-tanda tertentu (tag) untuk menyatakan kode-kode yang harus ditafsirkan oleh browser agar halaman tersebut dapat ditampilkan secara benar.
- HTML digunakan untuk menampilkan konten pada browser, seperti Text, Image, Video, Link, dan lain-lain.
- HTML bersifat statis. HTML hanya bertugas menampilkan konten yang diminta oleh developer.
 
Tools yang digunakan untuk membuat HTML : 
1.Browser
2.Code Editor (Visual Studio Code):
- Visual Studio Code adalah code editor yang dikembangkan oleh tim engineer Microsoft.
- Visual Studio Code dapat digunakan di Windows, Mac dan juga Linux


#### Dasar-dasar HTML

1. HTML Structure 
HTML tersusun sebagai kesatuan dari sebuah tingkatan (family tree relationship). Saat sebuah element berada di dalam element lain, maka disebut child element. Element yang berada diatas element lain disebut parent element.

2. HTML Anatomy
Terdapat tag pembuka, tag penutup, dan konten

3. HTML Element
Element Heading, Element Paragraph, Element Link

4. HTML Attribute
Attribute adalah properties dari sebuah HTML Element. Semua HTML Element memiliki attribute.

5. HTML Comment
Dengan menggunakan HTML Comment, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan. Comment ini pasti selalu ada dalam bahasa pemrograman apapun. Comment tidak akan dieksekusi oleh sistem. Comment hanya untuk dibaca oleh sesama programmer.


#### Cara menjalankan HTML
1. Kita bisa menjalankan HTML dengan mencari lokasi file HTML kita lalu membukanya via browser
2. install “Live Server” lalu kita bisa klik kanan pada file HTML kita dan ada pilihan open with “Live Server” maka HTML kita sudah auto reload

#### Cara membaca dokumentasi 
Untuk melihat seluruh element yang disediakan oleh HTML, kita bisa cek dokumentasi yang disediakan.

Cek dokumentasi :
- Resource by Mozilla
- Documentation by W3schools

#### HTML Tag Popular 
1. IMG : untuk menampilkan gambar
2. Alt : Alternative
3. Video : untuk menampilkan video
4. controls : untuk kita bisa mengatur videonya di play / pause dan indikator menit
5. Table 


**Rabu, 21 September 2022**

#### CSS Foundation


- CSS atau Cascading Style Sheets, yaitu bahasa yang digunakan untuk menentukan tampilan dan format halaman website.
- Dengan css kita dapat mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dll
- CSS berfungsi untuk menjelaskan dan menata tampilan elemen yang tertulis pada bahasa markup, salah satunya adalah HTML.


#### Structure CSS
- Struktur kode CSS terdiri dari tiga bagian: Selektor; Blok Deklarasi; Properti dan nilanya.


#### CSS Comment
Dengan menggunakan CSS Comment, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan. Comment ini pasti selalu ada dalam bahasa pemrograman apapun. Comment tidak akan dieksekusi oleh sistem. Comment hanya untuk dibaca oleh sesama programmer


#### Cara menggunakan CSS

1. Inline Style : Menambahkan CSS pada atribute element HTML
2. Bisa menggunakan Tag `<style>` pada file HTMl


#### CSS Files
Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML.


- CSS Tag Element : Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML.Kita bisa menggunakan Tag Elemen HTML secara langsung pada CSS. Jika menggunakan Tag Element, maka ini bersifat global.
- CSS - Tag Name : Kita bisa menggunakan Tag Elemen HTML secara langsung pada CSS. Jika menggunakan Tag Element, maka ini bersifat global.
- CSS - Class Name : Kita bisa menggunakan attribute class pada elemen HTML lalu memanggil nama class tersebut pada CSS
- CSS - Multiple Class : Kita dapat menggunakan lebih dari 1 class yang berbeda untuk 1 element HTML
- CSS - ID Name : Berbeda dengan Class Name. ID Name bersifat unik artinya hanya ada 1 nama ID pada 1 element HTML.
- Chaining Selectors : Chaining selector dapat kita gunakan pada case/kasus berikut. Jika kita memiliki 3 tag elemen HTML pada CSS namun kita ingin ada 1 elemen HTML yang memiliki styling berbeda.
- Nested Element : Konsep CSS sama dengan HTML yaitu setiap element memiliki parent dan child.
- Important CSS : Important CSS berada di level paling atas dari ID dan Class. Maksudnya adalah jika pada styling CSS kita menggunakan !important, maka styling sebelumnya baik itu ID Name atau Class Name akan di override.


**Kamis, 22 September 2022**

#### Algoritma & JS Dasar


**1. Algoritma**
- Suatu upaya dengan urutan operasi yang disusun secara logis dan sistematis untuk menyelesaikan suatu masalah untuk menghasilkan suatu output tertentu.
- Pada dasarnya fungsi utama dari algoritma adalah untuk memecahkan suatu masalah. Suatu algoritma pemrograman membawa keuntungan serta fungsi penting dalam aktivitas pembuatan program. Algoritma pada umumnya digunakan untuk membantu setiap orang yang ingin mengkonversikan sebuah permasalahan ke bahasa pemrograman.
	
    Ciri-ciri Algoritma :
    1. Input : Memiliki 0 atau lebih inputan
    2. Output : Memiliki min 1 buah output
    3. Definiteness : Instruksi jelas tidak ambigu
    4. Finiteness : Memiliki titik berhenti
    5. Effectiveness : Sebisa mungkin tepat sasaran dan efisien

    Penyajian Algoritma :
    1. Deskriptif : Penulisan algoritma dengan cara deskriptif seperti kita menulis tutorial (tata cara) dengan bahasa sehari-hari
    2. Flow Chart : Flow chart atau diagram alir, penyajian algoritmanya lebih mudah dibaca karena memiliki tampilan visual. Flow chart menggunakan simbol bangun datar sebagai representasi dari proses yg dilakukan.
    3. Pseudo Code : Pseudocode atau kode semu dapat diartikan sebagai deskripsi dari algoritma pemrograman yang dituliskan secara sederhana dibandingkan dengan sintaksis bahasa pemrograman. Tujuannya, agar lebih mudah dibaca dan dipahami manusia

**2. JS Dasar** 
- Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website
- Javascript juga dapat membuat website menjadi interaktif dan dinamis
- Javascript bisa digunakan untuk membuat fitur beragam seperti drag, drop komponen yang semuanya bisa bermanfaat untuk meningkatkan tampilan (interface) dan pengalaman menggunakan web. Selain itu, programmer juga bisa memperluas fungsi halaman web dengan menulis snippet Javascript untuk add-on pihak ketiga
- Menjalankan javascript umumnya browser pada setiap device user seperti Chrome dan Mozilla


#### Syntax dan Statement
- Syntax bisa dianalogikan seperti kosa kata (vocabulary) dan tata cara (grammar) pada bahasa pemograman.
- Kita menggunakan syntax tertentu untuk membuat statement program, instruksi untuk djalankan/dieksekusi oleh web browser, compiler, ataupun intrepreter
- Contoh Syntax : 
  1. Alert()
  2. Prompt()
  3. Confirm()
#### Console Log
- Console Log adalah hal yang krusial bagi developer web.
- Console log adalah tempat kita untuk cek logic pemograman web yang kita kembangkan
- Console log juga tempat kita untuk melakukan debugging (mengetahui error pada code) pada pemograman web

#### Comments 
- Comments adalah sintaks yang digunakan untuk memberi keterangan tentang suatu statement. Menggunakan bahasa inggris atau bahasa indonesia.
- Comments tidak akan dijalankan oleh program karena hanya untuk dibaca oleh sesama programmer ataupun diri sendiri untuk memahami maksud dan tujuan sebuah statement/syntax.

#### Tipe Data
- Tipe data adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming.
- Macam-macam tipe data :
  1. number : tipe data yang mengandung semua angka termasuk angka desimal.
  2. string : grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya.
  3. boolean : tipe data yang hanya mempunyai 2 buah nilai.
  4. null : tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai.
  5. undefined : tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.
  6. object : Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya)

#### Variable 
- Disemua bahasa pemograman, variable adalah container/tempat untuk menyimpan sebuah nilai
- Ada 3 cara mendefinisikan sebuah variabel :
  1. var 
  2. let 
  3. const

#### Operator
- Assignment operator (=) : untuk menyimpan sebuah nilai pada variabel.
- Increment dan Decrement : Gunakan increment atau decrement untuk menambah atau mengurangi sebesar 1 nilai.
- Arithmetic Operator : Tambah (+), Kurang (-), Perkalian (*), Pembagian (/), Modulus (%)
- Comparison operator adalah operator yang membandingkan satu nilai dengan nilai lainnya, contoh : 
  `<, >, <=, >=, ===, !===`
- Logical operator biasa digunakan untuk sebuah CONDITIONAL pada pemograman. Menghasilkan nilai BOOLEAN yaitu TRUE or FALSE.

**Jumat, 23 September 2022**

### JS Dasar Conditional & JS Dasar Looping


**1. JS Dasar Conditional**
- Conditional merupakan statement percabangan yang menggambarkan suatu kondisi.
- Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut
- Contoh 
  1. If Statement
  2. If Else Statement
  3. Else If Statement
  4. Truthy and Falsy
  5. Truthy and Falsy Assigment
  6. Switch Case Conditional
  7. Ternary operator

**2. JS Dasar Looping**
- Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
- Contoh :
  1. Manual Looping
  2. For Loop
  3. While Loop
  4. Do While
  5. Nested Loop


