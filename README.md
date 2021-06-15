# Nama : Safira Novianti
# NIM : 311910324
# Kelas : TI.19.A.2
# Praktikum 11 - PHP Framework

Beberapa ekstensi PHP perlu diaktifkan untuk kebutuhan pengembangan Codeigniter 4. Berikut beberapa ekstensi yang perlu diaktifkan:

php-json ekstension untuk bekerja dengan JSON; php-mysqlnd native driver untuk MySQL; php-xml ekstension untuk bekerja dengan XML; php-intl ekstensi untuk membuat aplikasi multibahasa; libcurl (opsional), jika ingin pakai Curl. Untuk mengaktifkan ekstentsi tersebut melalui XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini

![Xampp (2)](https://user-images.githubusercontent.com/56381081/122051560-ef9f7180-ce0e-11eb-9041-4bda698650fc.png)

![ekstensi php](https://user-images.githubusercontent.com/56381081/122051533-e8786380-ce0e-11eb-8154-52ceb2f560cb.png)

Kemudian buat folder baru dengan nama lab11_php_ci pada doc root webserver (htdocs)

![folder (2)](https://user-images.githubusercontent.com/56381081/122056478-d220d680-ce13-11eb-9e8f-5d8e2513d0f8.png)

# Installasi CODEIGNITER
Ada dua cara installasi Codeigniter, yaitu cara manual dan menggunakan composer. Pada praktik kali ini menggunakan cara manual:

Unduh Codeigniter dari website https://codeigniter.com/download Extrak file zip Codeigniter ke direktori htdocs/lab11_php_ci. Ubah nama direktory framework-4.x.xx menjadi ci4. Buka browser dengan alamat http://localhost/lab11_php_ci/ci4/public/

![local host](https://user-images.githubusercontent.com/56381081/122051540-ea422700-ce0e-11eb-97bc-d8bd52833e2f.png)

# Menjalankan CLI (Command Line Interface)
Arahkan lokasi direktori sesuai dengan direktori kerja project yang sudah dibuat (xampp/htdocs/lab11_php_ci/ci4/)

![tampilan command](https://user-images.githubusercontent.com/56381081/122051544-eca48100-ce0e-11eb-890b-324e92e43a04.png)

Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah php spark

![perintah CLI](https://user-images.githubusercontent.com/56381081/122051541-eadabd80-ce0e-11eb-84c8-fdfaea8ade7d.png)

Mengaktifkan Mode Debugging pada Codeigniter

![whoops](https://user-images.githubusercontent.com/56381081/122051551-edd5ae00-ce0e-11eb-8bc8-94a98b439ac8.png)