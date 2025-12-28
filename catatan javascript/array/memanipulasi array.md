# Memanipulasi array

* menambah elemen pada array
* menghapus elemen
* menampilkan seluruh isi array



### array method

* length untuk mengetahui jumlah elemen pada array
* join untuk menggabungkan seluruh isi array dan mengubahnya MENJADI STRING
* push, pop, shift, unshift  (ini untuk menambah dan menghapus elemen dalam array)
* push untuk menambah elemen array di akhir arry
* pop untuk menghilangkan elemen terakhir dari sebuah array
* unshift dan shift untuk elemen pertama
* unshift untuk menambah elemen baru di awal array
* shift untuk menghilangkan elemen pertama, sama seperti pop



* slice, splice
* splice untuk menyisipkan elemen array di tengah tengah
* rumusnya splice(indexAwal, mauDiHapusBerapa, elemenBaru1, elemenBaru2, ...)
* contoh implementasi:

&nbsp;	let namaPelanggan = \['saber', 'miyabi', 'vivy', 'anby', 'yanagi'];

&nbsp;	namaPelanggan.splice(3, 0, 'evelyn'); //ini artinya: 

&nbsp;								angka 3, mulai dari index ke 3

&nbsp;								angka 0, jumlah elemen yang ingin dihapus (0)

&nbsp;								'evelyn' tambah elemen baru, (bisa tambah lebih dari 1)





* forEach dan map
* forEach dan map ini seperti versi singkat atau cara pada array untuk looping menurutku pribadi
* untuk (forEach) ini hanya looping sederhana dengan function sebagai perantara, contoh:



&nbsp;	let angka = \[1,2,3,4,5,6,7,8]

&nbsp;	angka.forEach( function (e){

&nbsp;	console.log(e)

})

* hanya seperti itu saja, dan jika ingin mengakses indexnya, maka tambahkan 2 parameter (e, i) i untuk index dan e untuk element
* sedangkan untuk map, itu sama seperti forEach kurang lebihnya,
* hanya saja untuk map ini akan mengembalikan nilai karena memakai return, dan
* membuat array baru, array baru ini harus di tampung
* contoh prakteknya, menggunakan array yang sudah dibuat tadi (di atas)

&nbsp;	

&nbsp;	let angka2 = angka.map(function(e){

&nbsp;	return e;

&nbsp;	//atau e disini dapat dimanipulasi jika menggunakan map

&nbsp;	//return e \* 3

})



console.log(angka2);

* bisa dibilang mirip dengan function ekspresi
* selanjutnya ada METHOD SORT()
* ini berfungsi untuk mengurutkan elemen di dalam array
* itu saja
* jika () tidak di isi maka akan default
* oh, semua yang ada pada sort di convert menjadi string
* 
