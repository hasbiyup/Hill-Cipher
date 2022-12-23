# Hill-Cipher

Hill cipher adalah metode enkripsi yang menggunakan matriks sebagai kunci untuk mengubah teks biasa menjadi teks yang terenkripsi. Hill cipher memungkinkan enkripsi pesan yang panjang dengan menggunakan matriks yang lebih kecil daripada panjang pesan.

Untuk mengenkripsi pesan, Hill cipher memisahkan pesan menjadi blok-blok yang panjangnya sama dengan ukuran matriks kunci, dan kemudian mengalikan setiap blok dengan matriks kunci. Hasil dari perkalian ini adalah blok teks yang terenkripsi.

Untuk mendekripsi pesan yang terenkripsi, Hill cipher menggunakan invers matriks kunci untuk mengalikan blok terenkripsi dan menghasilkan blok teks biasa kembali.

Hill cipher sangat efektif dalam menjaga keamanan pesan, namun memiliki beberapa kelemahan. Misalnya, jika matriks kunci tidak memiliki invers, maka Hill cipher tidak dapat digunakan untuk mendekripsi pesan. Selain itu, Hill cipher juga rentan terhadap serangan ciphertext-only, di mana orang yang tidak memiliki akses ke kunci dapat mencoba menebak isi pesan dengan memeriksa padanan antara teks terenkripsi dan teks biasa yang diketahui.
