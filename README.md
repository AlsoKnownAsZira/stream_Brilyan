# Minggu 12
## Brilyan Satria Wahyuda
### TI-3H 2241720019

### Soal 3
<p>Keyword yield* digunakan dalam Dart untuk mendeklarasikan bahwa sebuah generator (fungsi async* atau sync*) akan menghasilkan semua nilai dari stream atau iterable lain. Dalam konteks kode yield* digunakan untuk menghasilkan nilai dari stream yang dihasilkan oleh Stream.periodic.</p>

### Soal 4

![Hasil Run Soal 4](soal4.gif)

### Soal 5
</p>Listen adalah metode untuk mendengarkan stream dan menerima data saat tersedia, Listen tidak memerlukan async<p>
<p>await for digunakan dalam fungsi async untuk menunggu dan iterasi nilai yang dihasilkan stream, await for perlu async</p>

### Soal 6
<p>Pada Langkah 8 akan dilakukan update initstate, terdapat inisialisasi numberstream, controller dan strea, setelah itu terdapat stream.listen, jika ada data baru yang di listen, setstate akan berjalan dengan mengubah lastnumber<br>
Pada langkah 10 akan dibuat function untuk menambahkan bilangan acak, menggunakan random.nextInt akan digenerate angka random dan disimpan di variable myNum, setelah itu angka yang ada di myNum akan ditambahkan ke sink stream numberStream
</p>

![Hasil Run Soal 6](soal6.gif)
