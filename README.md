# GIT
Selamat berkunjung di repository saya, semoga dengan artikel ini dapat berguna bagi teman - teman untuk mengetahui bagaiamana cara menggunakan *GIT* untuk pertama kali menggunakan *GIT*.

**Daftar Isi**
* [Apa itu GIT](#apa-itu-git)
* [Bagaimana cara menggunakan GIT](#bagaimana-cara-menggunakan-git)
    * [Instalasi GIT](#instalasi-git)
* [Penggunaan GIT](#penggunaan-git)
    * [Menambahkan Global Config](#menambahkan-global-config)
    * [Perintah Dasar Git](#perintah-dasarigit)
    * [Reposity Local](#reposity-local)
    * [Menambahkan File baru pada repository](#menambahkan-file-baru-pada-repository)
    * [*Commit* (Menyimpan perubahan ke database)](#*commit*-(menyimpan-perubahan-ke-database))
    * [Membuat repository server](#membuat-repository-server)
    * [Menambah Remote Repository](#menambah-remote-repository)
    * [Push (Mengirim perubahan ke server)](#push-(mengirim-perubahan-ke-server))
    * [Melihat hasilnya pada server repository](#melihat-hasilnya-pada-server-repository)
    * [Clone Repository](#clone-repository)
    
## Apa itu GIT

  **GIT** adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
 Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

## Bagaimana cara menggunakan GIT
Untuk pertama kali atau baru mencoba kita bingung bagaimana caranya menggunakan git begitu juga saya demikian pada awalnya, disini saya akan memberitahu kepada kalian **Bagaimana cara menggunakan GIT** jadi simaklah pada langkah - langkah dibawah ini.

### Instalasi GIT
Hal pertama yang harus kita lakukan adalah instalasi GIT pada komputer atau laptop pada laptop. berikut ini adalah bagaimana cara instalasi git dan penjelasan dari beberapa intruksi yang akan di instalasi nantinya.

untuk instalasi perhatikan hal - hal yang harus di lakukan pada langkah berikut ini :

1. Pertama, kunjungi link website https://git-scm.com/ untuk instalasi GIT
2. Jika sudah di beranda website, kita klik pada tulisan `Download 2.28.0 for Windows` untuk lebih jelas lihat pada gambar kotak hijau dibawah ini

      ![Instalasi GIT](instalasigit/download_git.png)

3. jika sudah maka installer git akan terdownload dan tunggu hingga selesai, langkah berikutnya buka installer git yang sudah terdownload dengan cara klik 2x atau klik kanan `Run as administrator`

      ![Instalasi GIT](instalasigit/download_git0.png)

4. Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik `Next` untuk melanjutkan instalasi.

      ![Instlasi GIT](instalasigit/download_git1.png)

5. Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](isntalasigit/download_git2.png)

6. Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pilih Vim Editor. Klik `Next` apabila Anda sudah menentukan file editor yang akan Anda gunakan

      ![Instalasi GIT](instalasigit/download_git3.png)

7. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih **Git from the command line and also from 3rd-party software** agar saat menjalankan perintah Git dapat dikenali di **Command Prompt (CMD)** pada Windows. Lalu Klik `Next`

      ![Instalasi GIT](instlasigit/download_git4.png)

8. Kemudian mengeksekusi SSH. Pilih Use OpenSSH, aplikasi default SSH dari Git. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git5.png)

9. Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih **Checkout Windows-style, commit Unix-style line endings**. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git6.png)

10. Setelah itu, disini terdapat 2 opsi, opsi pertama kita bisa gunakan MinTTY atau Command Prompt. Karena sudah friendly dengan CMD (Command Prompt), Maka saya memilih **Use Windows’ default console windows**. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git7.png)

11. Disini saya memilih default. Pada opsi ini kita bisa melakukan gitpull langsung dari server git, jika tidak bisa maka bisa membuat dengan metode penggabungan komit. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instlasigit/download_git8.png)

12. Pilih **Git Credential Manager** agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik `Next` untuk melanjutkan instalasi. 

      ![Instalasi GIT](instalasigit/download_git9.png)

13. Pilih Enable **File System Caching** agar Git memiliki fungsi system caching. Kedua, Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git10.png)

14. Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik Install untuk melanjutkan proses.

      ![Instalasi GIT](instalasigit/download_git11.png)

    Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.

      ![Instalasi GIT](instalasigit/download_git13.png)
      
15. Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui Command Prompt. Klik Win+R lalu ketik CMD untuk membuka Command Prompt seperti di bawah ini.

      ![Instalasi GIT](instalasigit/running.png)
      
    Selanjutnya masukkan perintah berikut `git --version` untuk cek versi git dan cek apakah Git sudah terinstall di komputer Anda. jika sudah maka tampilan akan di bawah seperti ini
      
      ![Instalasi GIT](instalasigit/cmd.png)

## Penggunaan GIT

 Cara Menggunakan Git
Setelah berhasil install ke Git, ikuti beberapa langkah untuk menggunakan Git. Berikut ini merupakan langkah menggunakan Git :

### Menambahkan Global Config

 Pertama kali untuk menggunakan GIT, kalian bisa mendaftarkan diri atau menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika sudah mendaftarkan diri buka Command Prompt (CMD) pada komputer atau laptop kalian dan tuliskan perintah - perintah di bawah ini lalau kita eksekusikan atau jalankan.

   * `git config --global user.name “nama_user”`
   
      digunakan untuk menyertakan nama pengguna dari akun git, hasilnya di bawah ini
   
      ![un](https://user-images.githubusercontent.com/72792261/96339471-23c76480-10bf-11eb-9638-4a34240f8ba8.png)
   
   * `git config --global user.email “nama_user”`
       
      digunakan untuk menyertakan pengguna email dari akun git, hasilnya di bawah ini
      
      ![ue](https://user-images.githubusercontent.com/72792261/96339469-21fda100-10bf-11eb-9cf0-219a5b46839f.png)
   
   * `git config --list`

      untuk mengetahui bahwa akun sudah terdaftar atau tidak, hasilnya di bawah ini

      ![ul](https://user-images.githubusercontent.com/72792261/96339470-232ece00-10bf-11eb-96db-bdcd738db7c1.png)
      
### Perintah Dasar Git

 Ketahui terlebih dahulu perintah - perintah dasar untuk memulai menggunakan git, berikut ini adalah perintah - perintah yang digunakan git.

   `git init`, perintah untuk membuat repository local
   
   `git add`, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
   
   `git commit`, perintah untuk menyimpan perubahan kedalam database git
   
   `git push -u origin master`, perintah untuk mengirim perubahan pada repository local menuju server repository
   
   `git clone [url]`, perintah untuk membuat working directory yang diambil dari repositry sever
   
   `git remote add origin [url]`, perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
   
   `git pull`, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

 Reposity Local

### Membuat Reposity Local, ikutilah langka - langka berikut ini untuk Reposity Local.

   * Buat direktori dengan nama bebas, untuk lokasi direktori bebas bisa di C:/ ataupun D:/, disini saya lokasi direktory di **C:\Users\Jose Fisto\Desktop\Pertama**. folder tersebut nantinya untuk menyimpan update file dari repository GitHub yang telah dibuat
   
      ![direktori](https://user-images.githubusercontent.com/72792261/96332802-6291f600-1090-11eb-8190-2807ada472c7.png)

   * jika sudah, selanjutnya kita buka direktory yamg sudah dibuat dengan cara klik kanan lalu pilih `Git Bash Here`, jika sudah nanti akan teralihkan ke *Git bash command*
   
      ![get_bash_here](https://user-images.githubusercontent.com/72792261/96333068-f7e1ba00-1091-11eb-9be6-1c60d9220ab8.png)
   
   * Buat direktori proyek praktikum pertama dengan nama apa saja, disini saya menamakannya "Sejarah". dengan perintah di bawah ini

      `mkdir Sejarah`
      
      ![mkdir_sejarah](https://user-images.githubusercontent.com/72792261/96333154-7dfe0080-1092-11eb-8e3d-9c52cfbff3af.png)
   
   * Jika sudah maka terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change
directory)

      `cd Sejarah`
      
      ![cd_sejarah](https://user-images.githubusercontent.com/72792261/96333513-94a55700-1094-11eb-9d2e-18155a76b356.png)
   
   * maka nanti direktory akan menjadi C:\Users\Jose Fisto\Desktop\Pertama\Sejarah
   
      ![slth_cd_sejarah](https://user-images.githubusercontent.com/72792261/96333514-95d68400-1094-11eb-94e4-40ad13b53318.png)
   
   * Jalankan perintah `git init`, untuk membuat repository local
   
      ![git_init](https://user-images.githubusercontent.com/72792261/96333450-2c567580-1094-11eb-9b23-f88d230fb40b.png)
      
   * Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git
   
   * Pada direktori tersebut, semua perubahan pada working directori akan disimpan.

### Menambahkan File baru pada repository
   
   * Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
   
   * disini kita akan coba buat satu file bernama README.md (text file)
   
     `$ echo “#Sejarah Komputer” >> README.md`
   
   * File **README.md** berhasil dibuat
   
      ![README_md](https://user-images.githubusercontent.com/72792261/96333982-86a50580-1097-11eb-9b85-035d4c8c2f73.png)
   
   * Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add
     
     `$ git add README.md`
     
   * File README.md berhasil ditambahkan.
   
      ![git_add](https://user-images.githubusercontent.com/72792261/96333980-84db4200-1097-11eb-90ee-4b7b561a41ba.png)
   
### *Commit* (Menyimpan perubahan ke database)

   * Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
   
     `$ git commit -m “Sejarah Komputer"`
     
   * Perubahan berhasil disimpan.
   
      ![Screenshot_1](https://user-images.githubusercontent.com/72792261/96335151-7ba2a300-10a0-11eb-9c2c-f1d4973c82f0.png)

### Membuat repository server

   * Server reopsitory yang akan kita gunakan adalah http://github.com
   
   * Anda harus membuat akun terlebih dahulu
   
   * Pada laman github, klik tombol start a project, atau
   
   * Dari menu (icon +) klik New Repository
   
      ![inikah](https://user-images.githubusercontent.com/72792261/96335318-1780de80-10a2-11eb-9bf9-3b74693bb326.png)

   * Isi nama repositorynya, misal: Prasejarah

   * lalu klik tombol Create repository.
   
      ![nambang](https://user-images.githubusercontent.com/72792261/96335407-9b3acb00-10a2-11eb-80cc-a552f2589479.png)
   
### Menambah Remote Repository

   * Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,
sehingga dapat diakses oleh banyak user

   * Untuk menambahkan remote repository server, gunakan perintah **git remote add origin [url]**.
     
     `$ git remote add origin https://github.com/josefisto/Prasejarah.git`
     
      ![git_remote_add_origin](https://user-images.githubusercontent.com/72792261/96336311-012a5100-10a9-11eb-8717-ff3fcbcbba9f.png)
      
### Push (Mengirim perubahan ke server)

   * Untuk mengirim perubahan pada local repository ke server gunakan perintah git push
        
        `$ git push -u origin master`
   * Perintah ini akan meminta memasukkan username dan password pada akun github.com.
   
      ![push](https://user-images.githubusercontent.com/72792261/96337397-10150180-10b1-11eb-84de-d939cf2e131c.png)
     
### Melihat hasilnya pada server repository

   * Buka laman github.com, arahkan pada repositorinya
   
   * Maka perubahan akan terlihat pada laman tersebut
   
      ![Print_out](https://user-images.githubusercontent.com/72792261/96336382-962d4a00-10a9-11eb-8d86-21829cba731c.png)
      
 ### Clone Repository
 
   * Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory)
   
   * Untuk melakukan cloning, gunakan perintah `git clone [url]`.
   
      ![cloning](https://user-images.githubusercontent.com/72792261/96337395-0d1a1100-10b1-11eb-8d4f-2af439f3599c.png)
