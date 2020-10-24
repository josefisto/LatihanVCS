---

Nama : Jose Fisto
NIM : 312010119
Kelas : TI.20 A.1
Prodi : Bahasa Pemrograman

      ![LogoUPB](upb.png)
---

#LatihanVCS
# GIT
Selamat berkunjung di repository saya, semoga dengan artikel ini dapat berguna bagi teman - teman untuk mengetahui bagaiamana cara menggunakan *GIT* untuk pertama kali menggunakan *GIT*.

**Daftar Isi**
* [Apa itu GIT](#apa-itu-git)
* [Bagaimana cara menggunakan GIT](#bagaimana-cara-menggunakan-git)
    * [Instalasi GIT](#instalasi-git)
* [Penggunaan GIT](#penggunaan-git)
    * [Menambahkan Global Config](#menambahkan-global-config)
    * [Perintah Dasar Git](#perintah-dasarigit)
    * [Membuat Repository Local](#repository-local)
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

      ![Instalasi GIT](instalasigit/download_git2.png)

6. Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pilih Vim Editor. Klik `Next` apabila Anda sudah menentukan file editor yang akan Anda gunakan

      ![Instalasi GIT](instalasigit/download_git3.png)

7. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih **Git from the command line and also from 3rd-party software** agar saat menjalankan perintah Git dapat dikenali di **Command Prompt (CMD)** pada Windows. Lalu Klik `Next`

      ![Instalasi GIT](instalasigit/download_git4.png)

8. Kemudian mengeksekusi SSH. Pilih Use OpenSSH, aplikasi default SSH dari Git. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git5.png)

9. Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih **Checkout Windows-style, commit Unix-style line endings**. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git6.png)

10. Setelah itu, disini terdapat 2 opsi, opsi pertama kita bisa gunakan MinTTY atau Command Prompt. Karena sudah friendly dengan CMD (Command Prompt), Maka saya memilih **Use Windows’ default console windows**. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git7.png)

11. Disini saya memilih default. Pada opsi ini kita bisa melakukan gitpull langsung dari server git, jika tidak bisa maka bisa membuat dengan metode penggabungan komit. Klik `Next` untuk melanjutkan instalasi.

      ![Instalasi GIT](instalasigit/download_git8.png)

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
   
      ![Menambahkan Global Config](PenggunaanGit/un.png)
   
   * `git config --global user.email “nama_user”`
       
      digunakan untuk menyertakan pengguna email dari akun git, hasilnya di bawah ini
      
      ![Menambahkan Global Config](PenggunaanGit/ue.png)
   
   * `git config --list`

      untuk mengetahui bahwa akun sudah terdaftar atau tidak, hasilnya di bawah ini

      ![Menambahkan Global Config](PenggunaanGit/ul.png)
      
### Perintah Dasar Git

 Ketahui terlebih dahulu perintah - perintah dasar untuk memulai menggunakan git, berikut ini adalah perintah - perintah yang digunakan git.

   `git init`, perintah untuk membuat repository local
   
   `git add`, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
   
   `git commit`, perintah untuk menyimpan perubahan kedalam database git
   
   `git push -u origin master`, perintah untuk mengirim perubahan pada repository local menuju server repository
   
   `git clone [url]`, perintah untuk membuat working directory yang diambil dari repositry sever
   
   `git remote add origin [url]`, perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
   
   `git pull`, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

### Membuat Repository Local

 Membuat Repository Local, ikutilah langka - langka berikut ini untuk Repository Local

   * Buat direktori dengan nama bebas, untuk lokasi direktori bebas bisa di C:/ ataupun D:/, disini saya lokasi direktory di **C:\Users\Jose Fisto\Desktop\Pertama**. folder tersebut nantinya untuk menyimpan update file dari repository GitHub yang telah dibuat
   
      ![Membuat Repository Local](PenggunaanGit/direktori.png)

   * jika sudah, selanjutnya kita buka direktory yamg sudah dibuat dengan cara klik kanan lalu pilih `Git Bash Here`, jika sudah nanti akan teralihkan ke *Git bash command*
   
      ![Membuat Repository Local](PenggunaanGit/get_bash_here.png)
   
   * Buat direktori proyek praktikum pertama dengan nama apa saja, disini saya menamakannya "Sejarah". dengan perintah di bawah ini

      `mkdir Sejarah`
      
      ![Membuat Repository Local](PenggunaanGit/mkdir_sejarah.png)
   
   * Jika sudah maka terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change
directory)

      `cd Sejarah`
      
      ![Membuat Repository Local](PenggunaanGit/cd_sejarah.png)
   
   * maka nanti direktory akan menjadi C:\Users\Jose Fisto\Desktop\Pertama\Sejarah
   
      ![Membuat Repository Local](PenggunaanGit/slth_cd_sejarah.png)
   
   * Jalankan perintah `git init`, untuk membuat repository local
   
      ![Membuat Repository Local](PenggunaanGit/git_init.png)
      
   * Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git
   
   * Pada direktori tersebut, semua perubahan pada working directori akan disimpan.

### Menambahkan File baru pada repository
   
   * Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
   
   * disini kita akan coba buat satu file bernama README.md (text file)
   
     `$ echo “#Sejarah Komputer” >> README.md`
   
   * File **README.md** berhasil dibuat
   
      ![Menambahkan File baru pada repository](PenggunaanGit/README_md.png)
   
   * Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add
     
     `$ git add README.md`
     
   * File README.md berhasil ditambahkan.
   
      ![Menambahkan File baru pada repository](PenggunaanGit/git_add.png)
   
### *Commit* (Menyimpan perubahan ke database)

   * Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
   
     `$ git commit -m “Sejarah Komputer"`
     
   * Perubahan berhasil disimpan.
   
      ![*Commit* (Menyimpan perubahan ke database)](PenggunaanGit/Screenshot_1.png)

### Membuat repository server

   * Server reopsitory yang akan kita gunakan adalah http://github.com
   
   * Anda harus membuat akun terlebih dahulu
   
   * Pada laman github, klik tombol start a project, atau
   
   * Dari menu (icon +) klik New Repository
   
      ![Membuat repository server](PenggunaanGit/inikah.png)

   * Isi nama repositorynya, misal: Prasejarah

   * lalu klik tombol Create repository.
   
      ![Membuat repository server](PenggunaanGit/nambang.png)
   
### Menambah Remote Repository

   * Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,
sehingga dapat diakses oleh banyak user

   * Untuk menambahkan remote repository server, gunakan perintah **git remote add origin [url]**.
     
     `$ git remote add origin https://github.com/josefisto/Prasejarah.git`
     
      ![Menambah Remote Repository](PenggunaanGit/git_remote_add_origin.png)
      
### Push (Mengirim perubahan ke server)

   * Untuk mengirim perubahan pada local repository ke server gunakan perintah git push
        
        `$ git push -u origin master`
   * Perintah ini akan meminta memasukkan username dan password pada akun github.com.
   
      ![Push (Mengirim perubahan ke server)](PenggunaanGit/push.png)
     
### Melihat hasilnya pada server repository

   * Buka laman github.com, arahkan pada repositorinya
   
   * Maka perubahan akan terlihat pada laman tersebut
   
      ![Melihat hasilnya pada server repository](PenggunaanGit/Print_out.png)
      
 ### Clone Repository
 
   * Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory)
   
   * Untuk melakukan cloning, gunakan perintah `git clone [url]`.
   
      ![Clone Repository](PenggunaanGit/cloning.png)
