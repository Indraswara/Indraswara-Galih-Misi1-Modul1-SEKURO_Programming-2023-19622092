<h1>Rangkuman video 6<h2>
<h2>Git Branch<h2>

 <p>
  <br>membuat branch baru di git 
  <br> ![image](https://user-images.githubusercontent.com/69344524/216504311-0cb7e1c7-567c-4b42-8c29-21a350eb1121.png) 
  
  <br>bisa dilihat di atas bahwa hanya ada satu branch 
  <br> ![image](https://user-images.githubusercontent.com/69344524/216504393-9f2c3926-6cf0-4a3c-ab05-ff4874aaf89f.png)
  <br> bisa dilihat branchnya bertambah dari yang hanya ada master sekarang menjadi 2 yakni, master dan testing. Sekarang kita berada di branch master 
   <br> ![image](https://user-images.githubusercontent.com/69344524/216504621-47310adf-667f-4bba-90e3-376accfd0034.png)
   <br>bisa dilihat bahwa kita berpindah ke branch testing dengan perintah git checkout <nama branch> 
   <br>![image](https://user-images.githubusercontent.com/69344524/216504857-1587213d-366d-4434-9ea1-18f1fca78926.png)
   <br>kita menambahkan file di branch testing dan melakukan commit ke dalamnya 
   <br> ![image](https://user-images.githubusercontent.com/69344524/216504977-692fe00b-1dc7-4396-bd35-08a257c1c8cb.png)
   <br>kita tambahkan branch baru lagi lalu kita pindah ke branch tersebut dan membuat dan commit file lagi 
   <br>![image](https://user-images.githubusercontent.com/69344524/216505135-4cfae0c3-8929-4f45-bd8a-4138441bed93.png)
   <br> ![image](https://user-images.githubusercontent.com/69344524/216505390-8d51649e-1c2e-469f-abe4-2ca994207a08.png)
   <br> ![image](https://user-images.githubusercontent.com/69344524/216505434-9693f912-0085-481f-a6bf-8fb46815c534.png)
   <br>bisa dilihat ada 1 file di masing-masing branch> nah, sekarang akan dilakukan merging 
 </p>
   
 <p>
   <br>ada dua tipe merging fast forward dan three way merge
   <br>![image](https://user-images.githubusercontent.com/69344524/216505753-861454c0-f15a-4cf8-aa14-8484ce1d98d5.png)
   <br>bisa kita lihat disini dilakukan sebuah merging antara master dan mahasiswa dan terjadi sebuah fast forward merging atau secara langsung
   <br> sekarang kita bisa hapus branch mahasiswa menggunakan git branch -d mahasiswa
   <br> sekarang merging antara master dengan branch testing 
   <br>![image](https://user-images.githubusercontent.com/69344524/216506696-2e82bf17-3acf-4d3f-881a-c7f86ff03976.png)
   <br>bisa dilihat berbeda karena ini three ways merge yang mana terjadi commit dulu sebelum dilakukan merge 
 </p>
