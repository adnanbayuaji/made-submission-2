# made-submission-2
Aplikasi katalog movie untuk submission kedua beasiswa MADE (Menjadi Android Developer Expert) dari Dicoding https://www.dicoding.com/academies/14/.

### Persyaratan aplikasi

* [x] Terdapat fitur untuk mencari film
* [x] Halaman detail untuk menampilkan detail fim yang telah dipilih pada halaman list film.
* [x] Tampilan poster dari film.
* [x] Navigasi untuk halaman upcoming, now playing, dan search.
* [x] Menggunakan recyclerview untuk menampilkan data bisa berupa list, atau card.
* [x] Halaman setting untuk mengganti bahasa atau localization. Aplikasi harus mendukung bahasa Indonesia dan bahasa Inggris.
* [x] Semua fungsi dari fitur project sebelumnya (Submission Project Catalogue Movie) harus tetap berjalan.

### Petunjuk menjalankan source code aplikasi

Untuk menjalankan source code aplikasi ini, anda perlu registrasi API KEY dari www.themoviedb.org
kemudian memasukkan API KEY yang telah didapat ke dalam file ***gradle.properties***

```
MovieDbApiKey="Masukan API KEY anda disini"
```

Kemudian tambah baris berikut pada file ***build.gradle*** dibawah ***buildTypes***

```
buildTypes.each {
        it.buildConfigField 'String', 'MOVIE_DB_API_KEY', MovieDbApiKey
    }
```

## Author

* **Adnan Bayu Aji**

Jangan lupa untuk follow dan ★
