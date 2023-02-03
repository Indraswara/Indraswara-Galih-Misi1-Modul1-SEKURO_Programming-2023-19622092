<h1> Rangkuman Video 5</h1>

<h2>Git Introduction</h2>

<p> 
  Pertama, kita install dulu git melalui websitenya 
  lsit command local dari git 
  - $ git init : inisialisasi repo di komputer lokal
  - $ git add <file(s)> : menambahkan file ke staging area
  - $ git status : menampilkan status repo saat ini ada file baru atau tidak
  - $ git commit : melakukan commit ke repo dari staging area dan akan terdeteksi di history
  - $ git config : digunakan untuk hal yang perlu di-setting untuk pertama kali seperti login akun github di git 
  - $ git brach : untuk mengetahui di branch mana kita saat ini 
  - $ git help 
</p>
  
<p>
  ada 3 area di dalam git 
  - working area : tempat dimana kita menulis source code
  - staging area : tempat seperti sebuah antrean sebelum kita melakukan push ke dalam history
  - history : tempat di mana semua commit terkumpul dan tercatat
</p>

<p>
  inisiasi repo di komputer lokal \n
  ![image](https://user-images.githubusercontent.com/69344524/216501704-5d69447b-4656-4b55-917f-461b8f242fc0.png)
  muncul tulisan master maka folder ini sudah menjadi repository \n
  ![image](https://user-images.githubusercontent.com/69344524/216501984-7c7dc655-9ebd-47cb-8efc-e224aab657c9.png)
  terdapat file baru yang belum di-track ke staging area
  
  ![image](https://user-images.githubusercontent.com/69344524/216502054-8b344048-b67d-4392-b4cf-933b368adb50.png)
  file sudah masuk ke staging area menggunakan git add <nama file(s)> 
  
  ![image](https://user-images.githubusercontent.com/69344524/216502171-a72517e4-26d3-4985-ae4a-518f1166ce74.png)
  sudah dilakukan commit ke dalam history dan diberikan pesan bahwa ini adalah commit pertama 

  ![image](https://user-images.githubusercontent.com/69344524/216502275-327b47b9-767b-49fd-bfc8-53914a8dd33c.png)
  sudah tidak ada lagi file baru yang terdeteksi sehingga working tree clean karena sudah dilakukan commit 
 </p> 
