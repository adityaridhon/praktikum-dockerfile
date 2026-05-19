# Aditya Ridho - 11231003 - Sister B
## Praktikum Dockerfile

Deskripsi singkat:
Repositori ini berisi kumpulan contoh dan materi praktikum terkait pembuatan dan penggunaan `Dockerfile`. Setiap subfolder berisi contoh kecil yang menunjukkan satu instruksi atau konsep Docker secara terpisah.


Penjelasan singkat beberapa folder `dockerfile/`:
- `01-FROM` : contoh penggunaan instruksi `FROM` (base image).
- `02-RUN` : contoh menggunakan `RUN` untuk instalasi saat build.
- `03-CMD` : contoh `CMD` untuk perintah default container.
- `05-ADD` / `06-COPY` : perbandingan `ADD` vs `COPY` dan efeknya.
- `07-DOCKERIGNORE` : contoh file `.dockerignore` untuk mengecualikan file saat build.
- `08-WORKDIR` : contoh mengatur working directory di image.
- `09-VOLUME` : contoh mendefinisikan volume.
- `10-EXPOSE` : contoh mengekspos port.
- `11-ENV` / `12-ARG` : contoh variabel lingkungan dan argumen build.
- `13-USER` : contoh menjalankan container sebagai user non-root.
- `14-HEALTHCHECK` : menambahkan pemeriksaan kesehatan pada container.
- `15-ENTRYPOINT` : contoh `ENTRYPOINT` versus `CMD`.
- `16-MULTISTAGE` : contoh build multi-stage untuk mengecilkan image.
