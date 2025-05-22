### 2.1 Run a server and three clients

![Run a server and three clients](images/2_1.png)

Pada gambar di atas, terlihat bahwa saat seorang client mengirimkan pesan, server langsung menerima pesan tersebut dan menyebarkannya ke semua client yang sedang terhubung—termasuk pengirimnya sendiri. Ini  karena server menyimpan daftar seluruh koneksi client yang sedang aktif dan terus memantau adanya pesan masuk dari salah satunya. Ketika sebuah pesan diterima, server secara otomatis mengirimkan pesan tersebut ke seluruh koneksi dalam daftar.

### 2.2 Modifying Port

![Modifying port](images/2_2.png)

agar dapat berjalan dengan baik, kita perlu untuk mengubah kedua port pada client dan server menjadi 8080, hal ini dikarenakan apabila keduanya baik memiliki port yang tidak sama maka client tidak akan dapat terhubung ke server.