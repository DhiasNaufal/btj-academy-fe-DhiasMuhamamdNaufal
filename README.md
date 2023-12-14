# FrontEnd Class by Dhias Muhammad Naufal

Repository ini merupakan repository dari kelas FrontEnd BTJ Academy. <br>
Repository ini akan terdiri dari `README` dan Folder `src` dan memiliki strktur seperti:

```
btj-academy-fe-DhiasMuhammadNaufal
|-- src/
|  |-- index.html
|  |-- about-me.html
|  |-- assets/
|  |  |-- image.png
|  |-- style/
|  |  |-- about-style.css
|  |  |-- about-style2.css
|  |  |-- index-style.css
|  |  |-- index-style2.css
|  |-- script.js
|  |-- about-script.js
|-- README.md
```

## Practical Exercise #4 : Javascript

Practical Excercise kali ini akan Mengubah Javascript menjadi syntax JQuery dalam halaman landing page seperti pertemuan sebelumnya. Fitur-fitrunya ialah : <br>

1. Logo di Sebelah Welcome berputar 360 derajat ketika di-`click`
2. Fitur Show Password
3. Fitur Form Valildation dan teks error ketika submit form dilakukan dan username kosong atau ketentuan password salah. Dengan
   Ketentuan password : minimal 1 huruf besar, 1 huruf kecil, 1 number, 1 symbol)
4. Fitur Form validation untuk ketentuan password dilakukan juga saat mengetik/menginput password.
5. Jika username dan password terisi, saat submit, page akan dialihkan menuju about page
6. Tambahkan warning jika caps lock pada keyboard ON, warning hilang jika caps lock Off
7. Tambahan Fitur Password dan Email Salah

### Apa yang berubah

1. Memperbaiki kesalahan pertemuan sebelumnya : Saat ini page `about-me` sudah diupdate dan logonya berputar
2. Mengubah syntax Javascript menjadi JQuery
3. Menambahkan fitur Email dan Password salah pada Landing Page (Karena tidak ada dalam server)

### Apa yang saya teumukan pada pertemuan 5

1. Syantax JQuery ternyata `Lebih mudah` diimplementasikan dibandingkan Javascript
2. Saya menggunakan Jquery Online, dan Downloaded File dan keduanya berjalan lancar, tetapi belum bisa menggunakan `pip install jquery`, i'll figure it out

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

<script src="jquery-3.7.1.min.js"></script>
```

3. Pada eror handling, method `.hide()` belum bisa digunakan karena logic yang digunakan pada kodingan saya masih menggunakan `.innerHTML("")` atau `.text("")` yang artinya mengkosongkan text pada elemen, bukan menyembunyikannya.. ini depends logic kodingannya.
4. Method `.click()` pada editor saya malah tercoret dan disuruh diganti menjadi `.on("click")`

### Fitur yang ditambahkan pada about page

1. Logo Berputar
2. Ganti tema menggunakan slider
3. `button` samping slider bisa berinteraksi dengan `hover` dan `click`
4. Gambar profil bisa berinteraksi dengan `click`
5. Gambar Education bisa berinteksi dengan `click`
6. Secret feature.. The secret feature will be discovered immediately.
