## NAMA : KHALIM <BR> NIM : 311910742 <br> KELAS: TI.19 B1
  
  # MEMBUAT DATABASE DAN TABLE
  Sebagai langkah awal kita akan membuat sebuah database terlebih dahulu. Diasumsikan kamu sudah mengetahui cara install MySQL entah itu standalone ataupun melalui paketan seperti XAMPP.   Sebelumnya yang perlu diingatkan adalah aturan penulisan nama table sama seperti membuat database. Untuk spesifikasinya penulis merekomendasikan dengan menggunakan huruf kecil dan dipisah dengan garis bawah “_” (tanpa kutip) sebagai pemisah.

Sekarang mari kita buat database dan table di MySQL dengan perintah berikut:
  
  <img width="610" alt="MEMBUAT_DATABASE" src="https://user-images.githubusercontent.com/81312138/120112958-68ad9080-c1a2-11eb-942d-2cca992df3f7.PNG">
 
  ## menambahkan data 
  
  <img width="558" alt="menambahkan_data" src="https://user-images.githubusercontent.com/81312138/120112972-81b64180-c1a2-11eb-9339-61035b84ab49.PNG">

# Membuat koneksi Database
  Fungsi ini diibaratkan sebagai cara untuk login kedalam MySQL Server. Fungsi mysql_connect() membutuhkan 3 argumen, dan mengembalikan nilai fungsi berupa ‘variabel koneksi’ ke MySQL. Jika koneksi dengan PHP gagal dilakukan, fungsi mysql_connect() akan mengembalikan nilai Boolean FALSE. Hasil FALSE ini akan disimpan dalam variabel $link dan bisa kita gunakan dalam perulangan IF untuk menampilkan error yang terjadi.
  
  <img width="692" alt="koneksi_berhasil_code" src="https://user-images.githubusercontent.com/81312138/120113093-1f117580-c1a3-11eb-9d92-e4b543773e98.PNG">
<img width="366" alt="KONEKSI_BERHASIL" src="https://user-images.githubusercontent.com/81312138/120113096-2042a280-c1a3-11eb-8a42-d088e415d559.PNG">

  # Membuat file indek Menampilkan data 
  
 hubungkan koneksi yang telah dibuat pada proses menampilkan data , Setelah semua kode kalian ketikan, silahkan kalian buka pada localhost nya dan bisa kalian lihat hasil akhir dari proses menampilkan data, jika kode diatas telah kalian ketikan dengan benar maka tidak akan terjadi error dan jika data yang ada pada database telah tampil semua pada kolom tabel, itu artinya proses menampilkan data berhasil sukses.
  
  <img width="606" alt="index1" src="https://user-images.githubusercontent.com/81312138/120113201-a52dbc00-c1a3-11eb-8024-b11d3ca2770c.PNG">
<img width="653" alt="index2" src="https://user-images.githubusercontent.com/81312138/120113203-a65ee900-c1a3-11eb-968e-234e4513e4d7.PNG">
<img width="654" alt="index3" src="https://user-images.githubusercontent.com/81312138/120113204-a6f77f80-c1a3-11eb-96f4-babfa302226a.PNG">
<img width="590" alt="index4" src="https://user-images.githubusercontent.com/81312138/120113205-a6f77f80-c1a3-11eb-92d4-60a3220b0043.PNG">

  <img width="610" alt="data_barang" src="https://user-images.githubusercontent.com/81312138/120113192-934c1900-c1a3-11eb-833b-8f3ec123e8e5.PNG">

# Menambahkan Data ( Create )
  form ini akan kita gunakan sebagai interface bagi pengguna untuk menginputkan data yang akan disimpan kedalam database.
  
<img width="648" alt="tambah1" src="https://user-images.githubusercontent.com/81312138/120113304-0e153400-c1a4-11eb-9cc6-fe4bb48b4647.PNG">
<img width="618" alt="tambah2" src="https://user-images.githubusercontent.com/81312138/120113305-0eadca80-c1a4-11eb-8ad1-ece16170c846.PNG">
<img width="603" alt="tambah3" src="https://user-images.githubusercontent.com/81312138/120113306-0f466100-c1a4-11eb-8b76-30b651d2ff09.PNG">
<img width="603" alt="tambah4" src="https://user-images.githubusercontent.com/81312138/120113307-0f466100-c1a4-11eb-8c35-8d7bf312b25f.PNG">
<img width="642" alt="tambah5" src="https://user-images.githubusercontent.com/81312138/120113308-0fdef780-c1a4-11eb-9e06-f60515541aab.PNG">
  <img width="645" alt="tambah" src="https://user-images.githubusercontent.com/81312138/120113302-0ce40700-c1a4-11eb-896a-b5a5ec12b858.PNG">
  
  # Mengubah Data (Update)
Buat file baru dengan nama ubah.php ,  menampilkan data yang sesuai dengan data yang dipilih oleh users berdasarkan parameter 
  
  <img width="607" alt="ubah1" src="https://user-images.githubusercontent.com/81312138/120113392-84b23180-c1a4-11eb-94ad-26d2e73be527.PNG">
<img width="653" alt="ubah2" src="https://user-images.githubusercontent.com/81312138/120113393-85e35e80-c1a4-11eb-9371-d42feafc3ee9.PNG">
<img width="664" alt="ubah3" src="https://user-images.githubusercontent.com/81312138/120113395-867bf500-c1a4-11eb-8407-742cc81a66a5.PNG">
<img width="650" alt="ubah4" src="https://user-images.githubusercontent.com/81312138/120113396-87148b80-c1a4-11eb-98af-7a8ebb1057d8.PNG">

  
  # Menghapus data ( delete )
  proses terakhir adalah sekarang kita akan membuat proses delete data dari database, konsepnya sama seperti proses update tadi cuman pada proses ini tidak menampilkan form, melainkan langsung menghapus data berdasarkan data yang dipilih oleh users pada halaman utama. silahkan buat script baru dengan nama delete.php dan ketik script berikut ini :
  
  <img width="555" alt="hapus" src="https://user-images.githubusercontent.com/81312138/120113409-909df380-c1a4-11eb-9ab2-32c55dbfd409.PNG">
