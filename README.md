# Challenge Javascript

> RULE:
- Tanpa Built-in Function
- Batas Tanggal akhir pengumpulan: Rabu, 9 Maret 2021 (00:00)
- Dikumpulkan di Drive Folder: Assignment > di tiap folder nama kalian > didalemnya buat buat Folder ChallengeW2 > masukan file js nya.

Soal
=======


1. Buatlah sebuah perulangan untuk menampilkan status ganjil-genap dari angka 1 hingga 100.

hasil output:
```javascript 
1 ganjil
2 genap
3 ganjil
4 genap
...
99 ganjil
100 genap
```

2. Buatlah sebuah perulangan dari soal nomor 1, namun hanya menampilkan angka kelipatan 3 saja.

hasil output:
```javascript 
3
6
9
...
93
96
99
```

3. Buatlah sebuah perulangan dari soal nomor 1, tanpa keterangan ganjil genap dan hanya menampilkan kelipatan 3, 5 dan 7

hasil output:
```javascript 
3
5
6
7
9
10
12
14
...
93
95
96
98
99
100
```

4. Ubahlah loop for berikut ke bentuk while

```javascript 
for (let i = 5; i < 10; i++) {
    console.log(i);
}
```

5. Sorting array dibawah dari kecil ke besar

```javascript 
[2, 6, 8, 3, 9]
```

6. Sorting array pada soal nomor 5, dari besar ke kecil

7. Pengelompokan array. Buatlah fungsi untuk mengelompokkan array menjadi multidimensional array kedalam 3 kategori. Genap, Ganjil dan Kelipatan 3.
   
```javascript 
grouping([1,2,3,4,5,6,7,8,9,10]);
// hasil output:
// [[2, 4, 8, 10], [1, 5, 7], [3, 6, 9]]

grouping([87, 50, 100, 2, 3, 74, 23]);
// hasil output:
// [[50, 100, 2, 74], [23], [87, 3]]

```

8. Balik kata: Buatlah sebuah function yang menerima input sebuah string dan mengembalikan urutan karakter yang sudah dibalik.

```javascript 
balikKata('javascript'); 
// hasil output:
// tpircsavaj

balikKata('salt academy');
// hasil output:
// ymedaca tlas
```

9. Ganti karakter: Buatlah sebuah function yang menerima 2 input berupa string dan array.
  Function akan mengembalikan string yang karakternya sudah direplace menjadi asterik.
  Asumsi input hanya menerima lowercase dan spasi.

```javascript 
gantiKarakter('salt academy', ['a', 'l']);
// hasil output:
// s**t *c*demy

gantiKarakter('javascript memang mudah', ['j', 'm']); 
// hasil output:
// *avascript *e*ang *udah
```

10. Konversi detik ke menit: Buatlah sebuah fungsi yang mengkonversi detik ke menit. (max 99:60).

```javascript 
konversi(100); // 01:40
konversi(120); // 02:00
konversi(0); // 00:00
konversi(615); // 10:15
```
