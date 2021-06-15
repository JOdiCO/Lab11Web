# Lab11Web
# PHP Framework (Codeigniter) 

### Darmawan Jodi Cahyo [311910457]

### TI.19.A.2


## Laporan Praktikum
### Persiapan
Mengaktifkan beberapa ekstensi php, diantaranya:
- php-json ekstension untuk bekerja dengan JSON;
- php-mysqlnd native driver untuk MySQL;
- php-xml ekstension untuk bekerja dengan XML;
- php-intl ekstensi untuk membuat aplikasi multibahasa;
- libcurl (opsional), jika ingin pakai Curl</br>
![mengaktifkan ekstensi_L01](https://user-images.githubusercontent.com/56252129/122025647-b6a5d380-cdf3-11eb-96a9-7e710acaddec.PNG)

Pada bagian extension, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.

![hilangkan titik koma](https://user-images.githubusercontent.com/56252129/122025706-c6bdb300-cdf3-11eb-97a6-34e5cb426bb5.PNG)

## Instalasi CodeIgniter 4
- Codeigniter dapat didownload dari website https://codeigniter.com/download
- Extrak file zip Codeigniter ke direktori htdocs/lab11_php_ci.
- Ubah nama direktory framework-4.x.xx menjadi ci4.
- Buka browser dengan alamat http://localhost/lab11_php_ci/ci4/public/
![instalasi codeigniter_l03](https://user-images.githubusercontent.com/56252129/122025788-d806bf80-cdf3-11eb-8495-06ba1bdd1738.PNG)

## Menjalankan CLI (Command Line Interface) 
Arahkan lokasi direktori sesuai dengan direktori kerja project dibuat (xampp/htdocs/lab11_ci/ci4/)  
Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah:`php spark`
![L04](https://user-images.githubusercontent.com/56252129/122025882-efde4380-cdf3-11eb-9acf-224f227d5876.PNG)

<br>Codeigniter juga menyediakan mode debugging/development yang dapat menampilkan error/kesalahan dalam kode program. Cara mengaktifkannya dengan mengubah nama file `env` menjadi `.env` kemudian buka filenya dan ubah nilai <b>CI_ENVIRONMENT</b> menjadi <b>development</b>.
![L05](https://user-images.githubusercontent.com/56252129/122025955-01bfe680-cdf4-11eb-8fc3-cff14b166856.PNG)

Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file
app/Controller/Home.php hilangkan titik koma pada akhir kode`(disini sebenarnya saya masih gagal mengubah <b>CI_ENVIRONMENT</b> menjadi <b>development</b> jadi tampilan nya menjadi seperti ini)`.
![L06](https://user-images.githubusercontent.com/56252129/122026500-772bb700-cdf4-11eb-998e-a89ae805bfd7.PNG)

