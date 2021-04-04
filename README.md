# Lab2Web
Belajar CSS
Nama : Alfin Nuris Setiadi 
NIM : 311910738 
Kelas : TI19B1 
Prodi : Teknik Informatika 
Mata Kuliah : Pemrograman Web 
Dosen Pengajar : Agung Nugroho, S. Kom., M. Kom

Pertanyaan dan Tugas

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![Screenshot (152)](https://user-images.githubusercontent.com/81596397/113498644-ed7c8500-9538-11eb-8891-a324128a6741.png)

gambar di atas code yang di tambah dan di ubah untuk membuat eksperimen.

penambahan di lakukan juga di HTML seperti gambar di bawah ini.

![Screenshot (154)](https://user-images.githubusercontent.com/81596397/113498700-8f9c6d00-9539-11eb-9697-cb92392ccb1f.png)

penambahan di css

![Screenshot (156)](https://user-images.githubusercontent.com/81596397/113498743-f752b800-9539-11eb-9f8c-b73dc3b4e85b.png)

dan hasilnya menjadi:

![Screenshot (157)](https://user-images.githubusercontent.com/81596397/113498770-28cb8380-953a-11eb-91a9-5e34b86d742a.png)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

Elemen h1 {...} yang dideklarasikan pada CSS mengacu pada style atau gaya teks saja yang ada di halaman awal web (sebagai header) atau memberi style CSS pada elemen HTML yang diingikan. Elemen h1 {...} mengacu pada Internal CSS yaitu menyisipkan CSS pada file HTML. 
contoh seperti gambar di bawah ini 

![Screenshot (159)](https://user-images.githubusercontent.com/81596397/113498885-2c133f00-953b-11eb-9635-3daf5152ee91.png)

sedangkan lemen #intro h1 {...} memiliki id maka penggunaan pada css dengan pagar (#) dan di dalam file index.html dalam pemanggilannya menggunakan id=" ". Elemen tersebut mengacu pada tampilan selector yang terdiri dari ID dan Class dimana ID selector ditandai dengan tanda pagar (#) di depannya.
contoh gambar seperti di bawah ini.

![Screenshot (161)](https://user-images.githubusercontent.com/81596397/113498925-9330f380-953b-11eb-9758-22e971eaf915.png)

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

Kode CSS internal diletakkan di dalam bagian pada halaman HTML. Class dan ID bisa digunakan untuk merujuk pada kode CSS, namun hanya akan aktif pada halaman tersebut (hanya 1 halaman). CSS internal diletakkan di dalam tag <style></style>. seperti contoh gambar.

![Screenshot (162)](https://user-images.githubusercontent.com/81596397/113499036-c1fb9980-953c-11eb-8285-8adf4857911b.png)

![Screenshot (163)](https://user-images.githubusercontent.com/81596397/113499291-ff612680-953e-11eb-86eb-a9caa1048241.png)

Dengan menambahkan CSS eksternal, perubahan apapun yang kita buat pada file CSS akan tampil pada website kita secara keseluruhan. File CSS eksternal biasanya diletakkan setelah bagian pada halaman.

![Screenshot (156)](https://user-images.githubusercontent.com/81596397/113499314-3b948700-953f-11eb-8a5e-4cade690b9cc.png)

ode Inline CSS ditulis langsung pada atribut elemen HTML. Setiap elemen HTML memiliki atribut style, di situ lah inline CSS ditulis.

![Screenshot (165)](https://user-images.githubusercontent.com/81596397/113499353-962de300-953f-11eb-88ba-3b9c8281de9d.png)

alhasil deklarasi yang akan tampil pada browser adalah semua dari ketiga deklarasi tersebut jika penggunaan dan penginputan ketika melakukan coding benar sesuai dengan peruntukkannya dan tidak ada error pada browser.

4.Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ("p id="paragraf-1" class="text-paragraf")

![Screenshot (166)](https://user-images.githubusercontent.com/81596397/113499441-426fc980-9540-11eb-9367-dab31e2a5de8.png)

Jika kita meng-klik button "Informasi selengkapnya", maka akan muncul tampilan pada halaman yang sama karena pada elemen HTML terdapat pemanggilan "intro".

![Screenshot (167)_LI](https://user-images.githubusercontent.com/81596397/113499519-c4f88900-9540-11eb-86fb-ff578f686090.jpg)
