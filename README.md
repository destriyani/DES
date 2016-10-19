# DES
implementasi DES menggunakan bahasa pemograman Java

# Kelompok 8
- Agung Yuliyanto (1411502550)
- Ahmad Raf Sanjani (1411501933)
- Ardha Sena (1411501875)
- Destriyani (1411501792)
- Kaishananda Dwi Takanwiedi (1411502980)
- Rizki Dharmawan Pohan (1411501164)


# Penjelasan mengenai program
  
  Melalui program yang kelompok saya buat, pesan yang diinputkan dapat secara automatis terenkripsi dan terdeskripsi dalam satu waktu sesuai aturan DES. Mengapa demikian? Karena apabila Ciphertext yang telah didapat dari proses enkripsi , diinputkan secara manual untuk kemudian mengalami proses deskripsi, yang terjadi malah akan mengalami error karena ada karakter yang tidak dikenali di dalam Ciphertext tersebut. Oleh karena itu hasil dari deskripsi akan tampil secara bersamaan dengan hasil enkripsi ketika program dijalankan. Untuk penjelasan lain yang lebih rinci, bisa dilihat langsung di dalam code yang kami unggah. Karena kami telah menyisipkan komentar berisi penjelasannya di setiap method yang ada, kecuali pada file program proses deskripsi. Karena pada prinsipnya, alur kerja yang dilakukan sama namun urutannya terbalik dimana pada round pertama key yang digunakan adalah K16 hingga sampai pada round ke-16, key yang digunakan dalah K1.
Berikut adalah gambaran singkat mengenai file program yang diunggah :
-	DES.java : merupakan induk dari program karena di dalamnya terdapat main method beserta method input yang dipanggil untuk dapat melakukan input Pesan dan Key. Input akan ditambahkan dengan spasi jika panjang pesan yang ingin dienkripsi tidak sama dengan nol apabila dimoduluskan dengan 0. 
-	SubKey.java : berisi class yang memuat variable yang  dibutuhkan, seperti S1 sampai S8 yang digunakan untuk proses SBOX, IP, Bitselect, P, IPInvers dimana proses-proses tersebut merupakan rangkaian tahap yang diperlukan untuk selanjutnya dapat melakukan proses enkripsi, deskripsi, PC1, leftshift, PC2, subkey yang digunakan untuk proses pencarian subkey.
Method-method seperti
BinaryToChar digunakan untuk mengubah binner ke karakter
GroupingText digunakan untuk mengelompokkan pesan agar menjadi 64-bit perblok
TextToBinnary mengubah string menjadi string binner
-	Encrypt.java : File ini memiliki method-method yang berfungsi untuk melakukan enkripsi.


# Kontribusi

  Disini peran saya dalam menyukseskan pengimplementasian DES ke dalam program adalah mencari sumber-sumber referensi dari beberapa paper yang ada di internet yang kemudian saya artikan ke dalam bahasa indonesia yang mudah untuk dimengerti agar anggota kelompok lain dapat terbantu dalam merangkai algoritma untuk membangun program yang sekarang dapat saya unggah disini.
