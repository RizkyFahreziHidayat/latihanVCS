Nama  : Rizky fahrezi hidayat

NIM   : 312010287

Kelas : TI.20.B.2

Cara Menggunakan Git dan Github:

  1.Install git terlebih dahulu(www.git-scm.com)
  
  2.Setelah download klik next saja terus lalu pilih install
  
  3.Setelah selesai install git, login ke github
  
  4.Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) atau Command Line (Linux)
  ![Screenshot (3)](htimages.githubusercontent.comtps://user-/73096887/96416825-ba5c6880-121a-11eb-92d6-01ac4e198691.png)
    
  5.Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
       
       $ git config --global user.name "UsernameAnda"
  
  6.Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.
       
       $ git config --global user.email IsiDenganEmailAnda@gmail.com
  
  7.Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.
       
       $ git config --list
  
  8.Login ke Github
  ![Screenshot (4)](https://user-images.githubusercontent.com/73096887/96416995-f7285f80-121a-11eb-995a-c1f81f8eb944.png)
  
  9.Buat akun terlebih dahulu
  
  10.Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
   ![Screenshot (5)](https://user-images.githubusercontent.com/73096887/96417023-00193100-121b-11eb-9787-f4474440c675.png)
   
  11.Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
    ![Screenshot (6)](https://user-images.githubusercontent.com/73096887/96417030-01e2f480-121b-11eb-88eb-cff47c3a8377.png)
    
  12.Setelah berhasil membuat folder pada local disk komputer Anda, buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 
    ![Screenshot (7)](https://user-images.githubusercontent.com/73096887/96417033-03acb800-121b-11eb-98de-2f98f04cab51.png)
    
  13.Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut
    ![Screenshot (8)](https://user-images.githubusercontent.com/73096887/96417037-05767b80-121b-11eb-9282-4e07e6f360bc.png)
    
       $ git init
   14.Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini
     ![Screenshot (9)](https://user-images.githubusercontent.com/73096887/96417043-08716c00-121b-11eb-86a4-513191c86fc9.png)
      
      ->Buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini kami membuat file index.txt(ubah ke README.txt)
      ->Buka GitBash lalu masukkan perintah berikut:
      
      $ git add README.txt
   
  
   15.Lalu setelah get init ketik seperti gambar di bawah ini
     ![Screenshot (10)](https://user-images.githubusercontent.com/73096887/96417050-0a3b2f80-121b-11eb-8863-f4fb2c5dd146.png)
     
       $ git status
  
   16.Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit
    
      $ git commit -m "first commit"
   
   17.Setelah git commit, lalu anda masukan git log
      ![Screenshot (10)](https://user-images.githubusercontent.com/73011140/96334624-5ca21200-109c-11eb-8f84-d24eb96a9d36.png)
        
        $ git log
     
   18.Lakukan Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository
        
        $ git remote add origin https://github.com/RizkyFahreziHidayat/LatihanVCS.git
   
   19.Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub
     ![Screenshot (11)](https://user-images.githubusercontent.com/73096887/96418321-ca754780-121c-11eb-82c8-e0e6ec21832a.png)
        $ git push -u origin main
     
      
     ->Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.
      
   20.Selesai anda sudah berhasil menginstall git dan menggunakan git dan github
