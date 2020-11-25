UExtract 4.2
============

uextract adalah alat untuk mengekstrak file arsip apa saja. [uextract](src/uextract) berasal dari [forum Puppy Linux](http://www.murga-linux.com/puppy/viewtopic.php?t=87864). Tetapi dapat digunakan di semua distro Linux.

Penggunaan
----------
Ekstrak:

    $ uextract file.tar.gz
    $ uextract file.deb
Melihat daftar isi arsip (tidak mengekstrak):

    $ uextract -l file.zip
Cek ketersediaan backend:

    $ uextract -b
Pemasangan
----------
    wget https://github.com/gnulinuxid/uextract/releases/download/v4.2-20201125/uextract-4.2.run
    chmod +x uextract-4.2.run
    ./uextract-4.2.run
Screenshot
----------
![uextract](screenshot.png)
