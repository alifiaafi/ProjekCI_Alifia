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
    
5.	Cara Install CI manual melalui website <br>
      •	Masuk ke website codeigniter.com kemudian pilih download <br>
      •	Pilih versi yang ingin anda gunakan, kemudian klik download <br>
      • Kemudian extract berkas, dan masukkan semua folder yang telah di extract ke dalam folder (buat baru) "belajar ci" <br> <br>
      
6.	Install melalui composer <br>
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

7.	Cara menjalankan framework setelah di install <br>
   Buka web browser dan ketikkan nama alamat localhost dari terminal tadi, yaitu http://localhost:8080 <br>
   ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/a1b9a178-66a9-43e7-a3e8-189e0d7fa0ed) <br> <br>

8. Koneksi Database <br>
   •	Buat database dengan nama ci4tutorial <br>
   •	Buat tabel dengan nama news dengan 4 kolom (id, title, slug, dan body) <br>
   •	Isikan tabel tersebut <br>
   •	Buat file baru (NewsModel.php) di dalam folder Models <br>
   ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/e0df4514-1213-4025-9507-842e34712c00) <br>
   • Tambahkan fungsi getNews
   ![image](https://github.com/alifiaafi/ProjekCI_Alifia/assets/134401933/d7b354be-5bf2-4512-9488-3bf1306e972d) <br>

9. Model, View dan Controller <br>
   • Model adalah kode yang bertugas untuk membuat pemodelan data dan dapat mengakses data dari database atau sumber lainnya. <br>
   • View adalah kode yang bertugas untuk membuat tampilan aplikasi. View berisi kode campuran dari PHP, HTML, JS, dan CSS. <br>
   • Controller adalah komponen yang bertanggung jawab untuk menerima permintaan dari pengguna, memproses permintaan tersebut, berinteraksi dengan model untuk mengambil atau memperbarui data, dan kemudian
     mengirimkan respons yang sesuai ke view. <br>

10. <br>
