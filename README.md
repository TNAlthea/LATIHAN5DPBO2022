# LATIHAN5DPBO2022
Repository ini bertujuan untuk memenuhi tugas latihan 5 pada mata kuliah Desain Pemograman Berorientasi Objek. 

------------------

- Nama : Sabian Annaya Havid
- Program Studi/Kelas : Ilmu Komputer/C2
- NIM : 2005021

*Saya Sabian Annaya Havid mengerjakan Latihan 5 dalam mata kuliah Desain Pemograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.*

------------------
## Penjelasan/Konsep program

a. Mengganti font dan ukuran teks

Mengganti font dan ukuran teks dapat dilakukan dengan mengklik salah satu bagian teks yang diinginkan seperti label, button, dan sejenisnya (yang memuat teks) yang akan memunculkan bagian palettes/properties pada bagian kanan program terlebih dahulu. Lalu, cari textarea yang berlabel 'font' dan semua opsi pilihan font, style, dan size akan muncul dan dapat dipilih sesuai kebutuhan. Pada program ini saya merubah font menjadi Futura dengan size 24 (heading) dan 14 (sisanya).

b. Mengubah nama variabel setiap komponen (misal komponen input NIM diberi nama variabel txtNim)

Mengubah nama variabel cukup mirip dengan metode untuk mengganti font yaitu dengan mengklik bagian elemen yang diinginkan hingga muncul bagian palettes/properties. lalu pilih sub-menu code dan cari textarea yang berlabel 'variable name' dan ketik nama variabel yang diinginkan.

c. Menambahkan validasi ketika inputan tidak lengkap, seperti memunculkan pesan error menggunakan class JOptionPane

![Data tidak boleh kosong](https://user-images.githubusercontent.com/99664611/159172281-1b67e54a-e7d5-41bc-a5d2-5887e9235b72.png)

Menambah validasi agar user tidak menginput data kosong dapat dilakukan dengan cara menambah bagian kode seperti bagian kode yang ditampilkan pada gambar tersebut. Pada prosesnya program akan membaca teks yang ada pada masing-masing textarea, lalu memanfaatkan fungsi isEmpty (bawaan library) untuk mengetahui apakah string yang terdapat pada textarea merupakan string kosong atau bukan. 

*note* Juga dapat menambahkan fungsi *trim()* sebelum fungsi *isEmpty()* untuk mensiasati apabila user hanya menginput spasi.

d. Menghapus data pada label inputan ketika sudah selesai add, update, delete, maupun ketika menekan tombol cancel

![clearText](https://user-images.githubusercontent.com/99664611/159172432-7f7b07d6-b9f7-43ab-96b0-f49002de75d7.png)

Menghapus tulisan pada textarea dapat dilakukan dengan cara mengset textarea dengan string kosong. Hal itu dapat dilakukan dengan memanfaatkan fungsi setText() seperti *NamaField.setText("")*

*note* saya menjadikan bagian kode tersebut sebagai fungsi tersendiri karena dipakai oleh beberapa prosedur lainnya.

e. Mengupdate tabel setiap kali ada perubahan pada data hasil add, update dan delete

mengupdate tabel dapat dilakukan dengan memanfaatkan fungsi *namaTabel.setModel(setTable())*

f. (bonus) Menambahkan atribut inputan baru selain yang sudah ada pada form, namun tetap berkaitan dengan data mahasiswa. Pastikan penambahan ini ditampilkan juga di tabel
- Tambah variabel private dan juga getter-setter terhadap variabel baru tersebut.
- Tambah parameter untuk variabel baru pada construct.
- Karena terdapat data dummy, maka perlu tambahan juga pada record data dummy tersebut.
- Dan juga karena perlu direpresentasikan dalam bentuk tabel, maka setTable juga perlu diubah dengan menambahkan variabel baru tersebut.
- Lalu perlu juga penyesuaian fungsi add, dan update terhadap variabel baru.

------------------
## Hasil menjalankan program

### Initial/Tampilan Awal

![Awal](https://user-images.githubusercontent.com/99664611/159171735-05c8f3cc-5176-4441-a33c-b8ef1bb6b2fd.png)

### Add

![Add](https://user-images.githubusercontent.com/99664611/159171754-7bef1472-d10f-41d6-a876-34747c68114e.png)

### Update

![Update](https://user-images.githubusercontent.com/99664611/159171761-fa46f395-a560-442d-b210-8a1deef23e17.png)

### Delete

![Delete](https://user-images.githubusercontent.com/99664611/159171772-7a2a8833-7e6d-442a-a3a5-9a6046adf6f1.png)

### Validation

![validation#1](https://user-images.githubusercontent.com/99664611/159171780-f2edec40-2735-48f7-b731-c2e9d0fd97a4.png)
![validation#2](https://user-images.githubusercontent.com/99664611/159171784-25c9def9-cff5-4e42-bcb2-e5663ac45ff5.png)
