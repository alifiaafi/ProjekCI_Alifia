# ProjekCI_Alifia
Nama : Alifia Muthi Afifa <br>
Kelas : TI 2D <br>
NPM : 220202076 <br>

Disini saya akan menjelaskan apa yang sudah saya pelajari tentang **FRAMEWOROK DAN CODEIGNITER** <br>

1. Pengertian Framework <br>
  **Framework** adalah Sebuah kerangka kerja yang digunakan untuk mengembangkan website. Framework ini dirancang untuk membantu developer dalam menyusun baris kode. <br> <br>
  
2. Fungsi framework <br>
    •	**Mempercepat pembuatan website** <br>
      Pengembang dapat menggunakan komponen-komponen yang sudah disediakan, sehingga tidak perlu menulis kode dari awal. <br> <br>
    •	**Meningkatkan keamanan** <br>
      Framework dapat meningkatkan keamanan website karena beberapa framework yang modern sudah mengadopsi berbagai sistem keamanan seperti SQL injection, autentikasi, enskripsi, dan sebagainya. <br> <br>
    •	**Mengorganisir kode** <br>
      Kode yang dituliskan menjadi lebih mudah dan terstruktur. <br> <br>
    •	**Mempermudah pemeliharaan dan perawatan website** <br>
      Perbaikan bug, maintenance menambah fitur dan meningkatkan keamanan website akan jadi lebih mudah karena kebanyakan framework sudah menggunakan pola arsitektur yang beragam. <br> <br>

3. Pengertian CodeIgniter <br>
  **CodeIgniter** adalah suatu framework PHP yang digunakan untuk membangun sebuah website dengan cepat berbasis MVC (Model-View-Controller) <br> <br>

4. Kelebihan CodeIgniter <br>
    •	Size yang kecil (hanya berkisar MB) <br>
    •	Fleksibel <br>
    •	Dapat dimodifikasi <br> <br>
    
5.	Cara Install CI (ada 2 cara) <br>
   a.	Install manual melalui website <br>
      •	Masuk ke website codeigniter.com kemudian pilih download <br>
      •	Pilih versi yang ingin anda gunakan, kemudian klik download <br>
   b.	Install melalui composer <br>
      •	Jalankan laragon (Start) <br>
      •	Klik Terminal <br>
      •	Kemudian tuliskan kode berikut <br>
      ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/b3741e38-f32c-4479-a444-b7e7510ac13c) <br>
      Untuk “belajarci” adalah nama project-root yang akan kita buat <br>
      •	Tunggu sampai proses instalasi selesai <br>
      •	Kemudian kita ubah root ke dalam project yang akan kita buat dengan menuliskan kode seperti dibawah ini <br>
      ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/f8ad40f0-944a-4035-a573-0ff251b56f6c) <br>
      •	Untuk mengetahui alamat localhost yang akan kita gunakan, maka kita tuliskan kode php spark serve. Untuk dibawah ini menggunakan alamat http://localhost:8080 <br>
      ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/6a228469-c01e-4bca-92d6-453473f64805) <br>
      •	Ketika tampilan website seperti gambar dibawah, maka kita sudah bisa mulai membuat website <br>
      ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/a1b9a178-66a9-43e7-a3e8-189e0d7fa0ed) <br> <br>
      
6.	Cara menjalankan framework setelah di install <br>
   Buka web browser dan ketikkan nama alamat localhost dari terminal tadi, yaitu http://localhost:8080 <br>
   ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/a1b9a178-66a9-43e7-a3e8-189e0d7fa0ed) <br> <br>

7. Koneksi Database <br>
   •	Buat database dengan nama ci4tutorial <br>
   •	Buat tabel dengan nama news dengan 4 kolom (id, title, slug, dan body) <br>
   •	Isikan tabel tersebut <br>
   ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/3e2866a3-67ca-469b-92ab-982f94993872) <br>
   •	Connect database dalam file .env
   ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/07ea7e39-3058-4e21-9caf-89524af20d34) <br>
   •	Buat file baru (NewsModel.php) di dalam folder Models <br>
   
