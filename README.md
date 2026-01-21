Langkah-Langkah Menjalankan Sistem Cek Ginjal dari GitHub

Langkah pertama adalah mengakses repositori GitHub sistem cek ginjal melalui alamat
https://github.com/widiyafrasiska/cekginjal
. Setelah halaman repositori terbuka, pengguna dapat mengunduh source code dengan memilih menu Code kemudian Download ZIP, atau menggunakan perintah git clone melalui terminal.

Setelah source code berhasil diunduh, langkah selanjutnya adalah menyiapkan lingkungan server lokal. Pengguna perlu menginstal web server seperti XAMPP atau Laragon yang telah mencakup Apache, PHP, dan MySQL. Setelah instalasi selesai, web server dijalankan hingga status Apache dan MySQL aktif.

Source code sistem cek ginjal kemudian dipindahkan ke dalam direktori web server, yaitu folder htdocs pada XAMPP atau folder www pada Laragon. Folder proyek disesuaikan dengan nama repositori agar mudah diakses.

Langkah berikutnya adalah menyiapkan database. Pengguna membuka phpMyAdmin melalui browser, kemudian membuat database baru sesuai dengan konfigurasi sistem. Setelah database dibuat, file database yang tersedia pada proyek diimpor ke dalam database tersebut agar tabel dan struktur data terbentuk secara otomatis.

Selanjutnya, pengguna melakukan pengaturan konfigurasi database pada sistem. File konfigurasi koneksi database dibuka dan disesuaikan dengan nama database, username, dan password MySQL yang digunakan pada server lokal.

Setelah konfigurasi selesai, sistem dapat dijalankan melalui web browser dengan mengakses alamat
http://localhost/nama_folder_proyek
. Apabila sistem tampil dengan baik, maka instalasi berhasil dilakukan.

Langkah terakhir adalah melakukan pengecekan fungsi sistem, seperti login, input data gejala, proses cek ginjal, dan penampilan hasil. Jika seluruh fitur berjalan dengan baik, maka sistem cek ginjal berbasis website siap digunakan.

untuk melihat halaman admin, pakar, dan pasien, dapat dilihat pada file username.txt
