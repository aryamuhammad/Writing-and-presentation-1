# Rangkuman Week 1

## Unix Command Line

-  ### Shell   
    Shell merupakan suatu program yang menerima perintah kita yang kemudian akan diteruskan kepada sistem untuk dieksekusi
- ### CLI (Command Line Interface)  
    CLI merupakan Shell yang berbasis teks
- ### Terminal   
    User membutuhkan suatu tempat/aplikasi untuk memberikan perintah kepada sistem. Tempat tersebut dapat kita sebut dengan Terminal. Kita dapat menggunakan shell di terminal.
- ### File System Structure 
  ![File Sistem Struktur](./asset/filesystem.png)  
  Dalam sistem, filesystem mengatur bagaimana data/file kita disimpan dalam sistem tersebut. biasanya disusun menggunakan struktur yang bentuknya mirip tree/pohon
- ### Command 
    - pwd (print working directory)  
        command untuk melihat current working directory
    - ls (list)  
        command untuk melihat isi file yang ada di direktori  
    - cd (change directory)  
        command untuk pindah ke direktori lain  
    - cat  
        command untuk melihat isi file
    - head  
        command untuk melihat beberapa line awal dari sebuah text file
    - tail  
        command untuk melihat beberapa line akhir dari sebuah text file
    - touch 
        command untuk membuat sebuah file
    - mkdir
        command untuk membuat sebuah direktori
    - cp
        command untuk menyalin file atau direktori
    - mv 
        command untuk memindahkan file atau direktori. command ini juga bisa digunakan untuk merename
    - rm 
        command untuk menghapus file atau direktori  
<!-- Github -->
## Git & Github
- ### Apa itu Git & Github
    Git adalah aplikasi yang dapat melacak perubahan yang terjadi pada file/folder. Biasanya digunakan oleh programmer untuk menyimpan file karena lebih efektif 
    Github adalah platform web based penyedia layanan git yang digunakan programmer untuk menyimpan atau hosting repository mereka 
- ### Why should use Git & Github
    Dengan menggunakan Git & Github, kita dapat berkolaborasi mengerjakan project yang sama tanpa harus copy paste folder aplikasi yang terupdate. Kita juga dapat membuat file dalam project yang sama dengan partner kita tanpa harus menunggu mereka menyelesaikan program.
- ### Alur Kerja Git & Github
    Create file -  git init - git add - git commit - git push
- ### Command pada Git 
    - git init <nama-project>. digunakan untuk membuat repository. 1 repo = 1 project = 1 direktori
    ![](git%20init.jpeg)  
    - git status. Digunakan untuk mengetahui status dari repository lokal
    - git add. Digunakan untuk menambahkan file baru pada repository 
    ![](git%20add.png)
    - git commit. Digunakan untuk menyimpan perubahan yang telah dilakukan pada lokal repository.
    ![](git%20commit.png)
    - git push origin. digunakan untuk mengpublish file ke remote repository Github.
    Caranya, pertama kita buat repository terlebih dahulu di Github
    ![](create-repo.jpeg)  
    setelah itu, kita push file yang ada di local repo kita dengan cara:
    ![](git%20push.jpeg)
    And, kita telah berhasil publish local repository kita ke Github
    ![](gitpush2.jpeg)
    - git clone. digunakan untuk 'mendownload' atau melakukan cloning dari Github ke lokal/komputer
    ![](gitclone.jpeg)
<!-- HTML -->
## HTML
- ### Peran HTML
    HTML adalah singkatan dari Hyper Text Markup Language. Peran dari HTML yaitu untuk menampilkan konten pada web/browser. Konten yand ditampilkan dapat **berupa** teks, gambar, video, link, dan lain-lain. 
- ### Tools HTML
    Tools utama yang harus dipersiapkan untuk membuat HTML adalah Browser dan juga Code Editor. Browser kita dapat menggunakan Google Chrome, Mozilla Firefox dll. Sedangkan untuk Code Editor kita dapat menggunakan VS Code, Sublime text ataupun yang lain
- ### HTML Sederhana
    - Element HTML
    ![](elementhtml..png)
    - Element HTML dengan Atribut
    ![](htmlattribute..png)
    Struktur HTML paling sederhana membuat element html, head, dan body   
    Contoh kerangka HTML sederhana:
    ![](kerangkahtml..png)
- ### Live Server
  Untuk dapat melihat file HTML kita di browser, kita dapat mengcopy path HTML kita.   
  atau kita dapat menggunakan Extension VS Code yaitu Live Server
  ![](liveserver.jpeg)
  Dengan menggunakan live server, kita dapat melihat file HTML kita di browser secara live.   
  Output:
  ![](ouputliveserver.jpeg)
- ### Popular Tag HTML
    HTML memiliki tag-tag yang paling sering digunakan ketika kita mendevelop sebuah website. Popular Tag HTML antara lain:
    - img
    ![](img..png) 
    - video
    ![](video..png)
    - table
    ![](table..png)
    - form
    ![](form..png)
- ### Semantic HTML
    Semantic HTML adalah penggunaan tag HTML yang sesuai dengan kebutuhan konten yang akan dibuat. Penggunaan Semantic HTML sangat membantu developer agar code kita lebih "Easy to read and understand". Kegunaan lain dari penggunaan Semantic HTML adalah meningkatkan aksesibilitas dan SEO Friendly.   
    Contoh Tag Semantic HTML: 
    ![](semantic..png)
- ### Deployment
    Deploy adalah proses untuk menyebarkan aplikasi yang sudah kita buat agar bisa digunakan oleh orang-orang.   
    **Gimana caranya?**   
    Kita bisa gunakan tools yang namanya **Netlify** nihh. Nanti kita tinggal daftar aja terus kita connect-in netlify kita dengan Github untuk mendeploy repository kitaa. Mudah kan?
<!-- CSS -->
## CSS
- ### Peran CSS
    CSS adalah bahasa yang digunakan untuk mendesain halaman website kita. Dengan menggunakan CSS, kita dapat mengubah warna, font, layout, dan lainnya pada website kita
- ### Basic Syntax CSS
    Struktur CSS sebagai berikut:    
    ![](./asset/taghtmlcss..png)
    Penjelasan
    - h1  
    h1 adalah selector berupa element HTML yang akan diubah
    - color   
    color merupakan property CSS berupa bagian mana yang akan diubah. 
    - red   
    red adalah value yaitu nilai dari property CSS   
- ### Cara Menyisipkan CSS ke HTML
    Ada tiga cara untuk menyisipkan CSS ke HTML
    - inline CSS
    ![](./asset/inlinecss..png)
    - tag style
    ![](./asset/tagstylecss..png)
    - .css file
    ![](./asset/cssfiles..png)
- ### Styling HTML
    Contoh melakukan styling pada element HTML:  
    ![](./asset/stylinghtml..png)
    Kita lakukan sytling pada CSS
    ![](./asset/stylingcss..png)

- ### Responsive Web Design 
    Responsive Web Design adalah bagaimana caranya kita dalam mendesain dan styling website kita terlihat rapih di semua tipe device. Responsive Web Design akan secara otomatis menyesuaikan perbedaan lebar dan tinggi layar ketika membuka website kita. Kita dapat membuat Responsive Web Design dengan CSS Flexbox & Grid 
- ### Flexbox
    - Flexbox adalah salah satu cara untuk mengatur layout pada CSS. Flexbox memiliki kemampuan untuk menyesuaikan layout secara otomatis. Flexbox memiliki flexbox container dan juga flexbox items   
    ![](./asset/flexboxhtml..png)
    styling CSS:
    ![](./asset/flexboxcss..png)
    Output:
    ![](./asset/outputflexbox.jpeg)
    Keterangan:
      - div background biru merupakan container flex
      - div dengan warna kuning merupakan item dari container flex
    - Property Flexbox
      - justify-content, untuk mengatur tata letak secara horizontal
      - align-items, untuk mengatur align dari item secara vertikal
<!-- Algoritma -->
## Algoritma & Data Structures
- ### Perbedaan
    - Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah
    - Data Struktur adalah cara menyimpan dan mengatur data secara terstruktur pada sistem komputer atau database sehingga lebih mudah diakses.
- ### Manfaat
    Dengan mempelajari algoritma dan data struktur,  membuat programmer lebih mudah dalam mengelola sebuah data dan juga membantu menyelesaikan permasalahan menggunakan data tersebut secara efisien
- ### Membuat Algoritma Sederhana
    Contoh algoritma sederhana untuk mengkalikan 2 angka yang diinput oleh user   
    Step 1 : Mulai
    Step 2 : Deklarasikan variabel angka1, angka2, dan perkalian
    Step 3 : Ambil nilai angka1 dan angka2
    Step 4 : Kalikan angka1 dan angka 2 dan masukkan hasilnya ke variable perkalian
    Step 5 : Tampilkan hasil perkalian
    Step 6 : Selesai   
- ### Menerapkan Algoritma ke bahasa pemograman
    Implementasi ke bahasa Javascript
    ![](./asset/algosederhanaperkalian..png)
- ### Algoritma dengan Javascript
    Contoh mengerjakan project di google slide. Mencari nilai max dari dua nilai yang diberikan.
    ![](./asset/algonilaimax..png)

<!-- JS -->
## Javascript
- ### Intro to Javascript
    - Apa itu javascript? 
        Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website. Javascript membuat website kita menjadi lebih interaktif
    - Bagaimana menjalankan Javascript? 
        Javascript dijalankan pada website device setiap user
    - Syntax Javascript 
      - alert()
      - prompt()
      - confirm()
      - console.log()
        ![](./asset/syntax..png)
    - Tipe data   
      - number
      - string
      - boolean
      - null
      - undefined
      - object
    - Variable   
      - var
      - let
      - const 
        ![](./asset/variabel..png)
- ### Conditional
    - Apa itu conditional?  
        Statement percabangan yang menggambarkan suatu kondisi. If condition akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut   
        Contohnya: jika cuaca hari ini hujan, maka kita membawa payung
    - Latihan
        ![](./asset/conditional..png)
- ### Looping
    - Apa itu looping?
        Statement yang mengulang sebuah instruksi hingga kondisi terpenuhi
    - Latihan
    ![](./asset/forloop..png)