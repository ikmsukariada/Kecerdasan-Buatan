Penjelasan DFS :

Baris 2-9: graph akan direpresentasikan menggunakan daftar adjacency - agar lebih mudah kita akan menggunakan Python yiatu dengan menggunakan struktur data dictionary. Setiap vertex menyimpan daftar node yang saling berkaitan.

Baris 11: fungsi visited berikut merupakan set yang digunakan untuk melacak node yang akan dikunjungi.

Baris 21: disini dfs dipanggil dan melewati set yang dikunjungi, dan dipresentasikan dalam bentuk dictionary dimana 1 yang merupakan simpul awal.

Baris 13-18: jadi pada fungsi berfungsi untuk memeriksa apakah node saat ini belum dikunjungi - jika ya, akan ditambahkan dalam set yang sudah dikunjungi. Kemudian untuk setiap keluarga dari node saat ini, fungsi dfs dipanggil lagi. Fungsi akan kembali ketika semua node sudah dikunjungi.

Penjelasan BFS :

baris 1 - 12 : graph akan direpresentasikan menggunakan daftar adjacency - agar lebih mudah kita akan menggunakan Python yiatu dengan menggunakan struktur data dictionary. Setiap vertex menyimpan daftar node yang saling berkaitan.

Baris 14: fungsi visited berikut merupakan set yang digunakan untuk melacak node yang akan dikunjungi.

Baris 15: fungsi ini akan membuat antrian yang akan digunakan untuk melacak node saat ini dalam sebuah antrian.

Baris 31: fungsi bfs ini akan memberikan daftar yang sudah dikunjungi dan akan dipresentasikan dengan grafik dalam bentuk dictionary, dan simpul awalnya adalah 1.

Baris 17-28: Dalam algoritma BFS, simpul anak yang telah dikunjungi disimpan dalam suatu antrian. Antrian ini digunakan untuk mengacu simpul-simpul yang bertetangga dengannya yang akan dikunjungi kemudian sesuai urutan pengantrian.

fungsi ini akan berlanjut sampai antriannya  kosong.
