# python-modules

Untuk pertama kali ketika web dipanggil, maka akan memanggil
file manage.py

Struktur File:

manage.py: jalan pintas untuk menggunakan utilitas command-line Django-admin. Ini digunakan untuk menjalankan perintah manajemen yang terkait dengan myproject. kita akan menggunakannya untuk menjalankan server pengembangan, menjalankan tes, membuat migrasi dan banyak lagi.

__init__.py: file kosong ini memberitahu Python bahwa folder ini adalah paket Python (dalam folder proyek: pydjango)

settings.py: file ini berisi semua konfigurasi proyek. kita akan merujuk ke file ini setiap saat! (dalam folder proyek: pydjango)

urls.py: file ini bertanggung jawab untuk memetakan rute dan jalur dalam myproject. Misalnya, jika Anda ingin menampilkan sesuatu di URL / about /, Anda harus memetakannya terlebih dulu di sini. (dalam folder proyek: pydjango)

wsgi.py: file ini adalah antarmuka gateway sederhana yang digunakan untuk penyebaran. Anda tidak perlu repot-repot. Biarkan saja sekarang. (dalam folder proyek: pydjango)