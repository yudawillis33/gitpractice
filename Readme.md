	LAPORAN TUGAS ALGORITMA PEMROGRAMAN 2 GIT

Nama 	: Fadillah Willis Triyayuda
NIM 	: 162012133074

#Langkah 1 : Membuat Repository baru pada file yang diinginkan

Pembuatan Repository baru dapat dilakukan dengan cara sebagai
berikut:

1. Membuat Folder pada directory yang diinginkan dengan nama
2. Buka Command Line git
3. ketik "ls" untuk mengetahui dimana directory anda sekarang

--Percobaan tugas dengan file C:/UNAIR/gitpractice--

4. untuk mengakses file C ketik "cd C"
5. lalu ketik "cd UNAIR"
6. Kemudian ketik "cd gitpractice"
7. Setelah itu ketik "ls" kembali untuk mengkonfirmasi anda
sudah pada folder gitpractice

#Langkah 2 : Membuat Repository pada file "gitpractice"

1. ketik "git init" pada Commandline untuk membuat repository
2. Buka notepad dan tulis laporan praktikum pembuatan repository
pada git
3. Setelah selesai, klik "save.as" pada file notepad yang
telah dibuat
4. Rename file dengan format "Readme.md"
5. Save pada folder "gitpractice" yang telah dibuat

#Langkah 3 : Melakukan commit untuk file "Readme.md"

1. ketik "git add Readme.md" untuk memindahkan file Readme.md
ke staging area
2. ketik "git status" untuk melihat file apa saja yang saat
ini ada di staging area
3. ketik "git commit" untuk melakukan commit file yang sebelumnya
sudah dipindahkan di staging area untuk di commit

#Langkah 4 : Membuat Cloning Repository pada github.com

1. Buka github.com dan lakukan login atau register akun anda
2. Membuat New Repository pada simbol "+" pada kanan atas layar
3. Mengisi kolom nama repository lalu create
4. ketik "git commit -m "first commit"" pada Command Line
untuk menginisiasi commit pertama kali
5. ketik "git branch -M main" pada Command Line untuk membuat
main branch pada repository 
6. ketik "git remote add origin https://github.com/yudawillis33/gitpractice.git"
untuk menambahkan repository kita pada github di link yang sudah dibuat
sehingga git mengetahui pada saat ingin push local repository lalu kemana
link remote repository yang akan menyimpan file kita 
7. ketik "git push -u origin main" untuk mengeksekusi push file
dari local repository ke cloud remote repository yaitu github





