latihan1
#latihan1
cara penggunaan git
1. install git terlebih dahulu
2. buka aplikasi git dan jalankan perintah "git config --global 
user.nama "nama anda" lalu enter dan tulis "git config --global 
user.email "email anda"

menggunakan git 
1. buka github.com
2. tambahkn repository baru
untuk mengisi ada beberapa hal yang harus diperhatikan :
a. repository name : nama repository (latihan1)
b. description : deskripsi repository (biasanya berupa siapa saja yang 
terlibat)
c. public/private : kondisi repository mau di publikasikan atau pribadi
d. initiallize the repository with README : ini adalah isi dokumentasi 
pada project yang dikerjakan, saya sarankan tidak usah dicentang.
setelah diisi sesuai keinginan, klik tombol "create repository"
maka tampilan selanjutnya adalah repository yang sudah dibuat, tahap 
selanjutnya adalah upload project ke repository online.
3. buka aplikasi git bash. pertama kalian konfigurasi seperti yng sudah 
dijelaskan diatas
4. buat directory project praktikum pertama dengan nama latihan1
5. sehingga terbentuk satu direktori baru dibawahnya,selanjutnya masuk 
kedalam direktori tersebut dengan perintah cd
6. direktori aktif menjadi d/latihan1
7. jalankan perintah git init, untuk membuat repository lokal
8. repository baru berhasil diinisialisasi, dengan terbentuknya satu 
direktori hidden dengan nama .git
9. pada direktori tersebut semua perubahan akan tersimpan
10. untuk membuat file dapat menggunakan text editor, lalu menyimpan 
filenya pada direktori aktif (repository)
11. buat satu file bernama README.md
12. file README.md berhasil dibuat
untuk menambahkan file yang baru dibuat tersebut gunakan perintah git 
add
13. file README.md berhasil ditambahkan
14. untuk menyimpan perubahan yang ada kedalam database repository 
lokal, gunakan perintah git commit -m  "komentar commit"
15. perubahan berhasil disimpan
16. server repo yang akan digunakan adalah https:/github.com
17. remote repository adalah repository server yang akan digunakan untuk 
menyimpan setiap perubahan pada lokal repository, sehingga dapat diakses 
oleh banyak user
18. untuk mengirim perubahan pada lokal repository ke server gunakan 
perintah git push 
19. perintah ini akan meminta anda memasukkan username dan password pada 
akun github.com
20. buka halaman github.com, arahkan pada repository lalu refresh. maka 
hasilnya akan ditampilkan.
