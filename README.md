# LATIAN-PYTHON
<br> NAMA: INDAH REMBULAN CAHYA
<br> NIM: 311910019
<br> TUGAS BAHASA PEMROGRAMAN

MEMBUAT DAN MENAMBAHKAN FILE REPOSITORY

# 1. pertama install apllikasi terlebih dahulu, download sesuai os kamu.. bisa download di (http://git-scm.com)
   
   
  ![1](https://user-images.githubusercontent.com/57023379/67627748-890dbe80-f88c-11e9-9ca5-d4096a869422.PNG)

# 2. buat akun github di server kamu (github.com)

# . lalu tambahkan global config
  - lakukan kongfigurasi user name dan user email anda ke git dengan cara
  - buka aplikasi git
  - ketikan perintah
  git config --global user.name "user name hub kamu"
  git config --global use.emai "email hub kamu"
  
  ![6](https://user-images.githubusercontent.com/57023379/67627808-937c8800-f88d-11e9-9dfd-7a842e1ee5e2.png)

  
# 4. membuat respitory local

  -buat folder baru di windows explorer contoh d;\bahasa pemrograman
  -klik kanan dan pilih git bash
  
  ![4](https://user-images.githubusercontent.com/57023379/67627824-dc344100-f88d-11e9-8a5e-76c576243f8b.png)

  -setelah ke git bash command buat direktori latihan kamu contohnya latihanpytn1
   $mdkr latihanpytn1
   $cd latihanpytn1
   ![28 (2)](https://user-images.githubusercontent.com/57023379/67627847-5795f280-f88e-11e9-92cd-74549ff5a638.PNG)

  
   
# 5. membuat respitory local
   -jalankan perintah $git init
   -jika berhasil akan ada folder tersembunyi dengan nama .git didalam folder latihanpytn1
   
   ![28 (2)_LI](https://user-images.githubusercontent.com/57023379/67627866-c410f180-f88e-11e9-904b-1f70615fa123.jpg)

  
   
# 6. menambahkan file baru di respitory
   -kita coba membuat file baru yang bernama README.md
   -jalankan perintah $echo "#latihanpytn1">>README.md
   -file README.md berhasil dibuat
   
   ![28 (3)_LI](https://user-images.githubusercontent.com/57023379/67627885-3386e100-f88f-11e9-9824-cecea173c648.jpg)

   
   -tambahkan file tersebut kedalam repository kamu dengan perintah $git add README.md
   
   ![30 (2)](https://user-images.githubusercontent.com/57023379/67627899-88c2f280-f88f-11e9-8366-02c09bd2e71f.PNG)

   
 # 7. simpan perubahan kedata base commit##
    -gunakan perintah git commit-m "file pertama"
    
    ![30 (2)_LI](https://user-images.githubusercontent.com/57023379/67627923-d8a1b980-f88f-11e9-82a7-2f57d8597e3c.jpg)

    perubahan berhasil dibuat
    
    
  # 8. membbuat repository server
  
     -pastikan github account kamu sudah diverifikasi terlebih dahulu
     -masukan ke akun kamu dan klik tombol+ yang ada dipojok kanan
     -klik new repository
     -masukan repository name contoh: latihanpytn1
     -uncheklis pada intialize this repository with a README agar memudahkan tutorial pembelajaaran ini 
     -kemudian klik creae respitory
     
     ![5](https://user-images.githubusercontent.com/57023379/67627943-0b4bb200-f890-11e9-86a0-a58310936e3c.png)

     
     
# 9. menambahkan remote respitory 
   
      -remote respitory merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, 
      sehingga bisa diaksess oleh banyak user.
      -untuk menambahkan gunakan perintah "git remmote add origin [url]"
      - contoh $git remote origin http://github.com/indahrembulancahya/latihanpytn1.git
      
     ![30 (2)_LI](https://user-images.githubusercontent.com/57023379/67627923-d8a1b980-f88f-11e9-82a7-2f57d8597e3c.jpg)


# 10. mengirimkan ke server push 
   
       -untuk mengirim perubahan local repository keserver gunakan perintah git push 
       $git push -u origin master 
       -nanti akan diminta email dan password kamu pastikan input dengan benar
       
       ![13](https://user-images.githubusercontent.com/57023379/67628062-3f27d700-f892-11e9-807e-72df5985a2d0.png)

       
       
 #  11. finish
   
       -untuk melihatnya coba buka laman (http://github.com) arahkan pada repository yang anda buat tadi
       -maka perubahan dapat terlihat dengan munculnya file readme.md disitu
       
       ![26](https://user-images.githubusercontent.com/57023379/67628072-68e0fe00-f892-11e9-8630-0fc72f555144.jpg)
       
       #SEKIAN DAN TERIMAKASIH

  
