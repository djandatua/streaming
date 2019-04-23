:::::::::::::::::::::::::::::::::::::::::::::::::::::::::
::: Hello there! Thanks for Visiting Fajar Ru's Note! :::
::::::::: https://penguinstunnel.blogspot.co.id :::::::::
::::::::::::::::::::::::::::::::::::::::::::::::::::::::: 

## NOTICE
Sebelum menggunakan, harap untuk membaca serta
memperhatikan Lisensi yang digunakan.
Dengan menggunakan Paket ini, berarti anda setuju dan 
tunduk kepada Lisensi-lisensi tersebut!

## INFO PAKET
Nama		: NGINX RTMP Stream Precompiled Package
Versi Paket	: NGINX 1.11.9
Saran Distro	: Ubuntu 16.04 (Xenial Xerus)


## DESKRIPSI PAKET
Paket yang teman-teman download merupakan paket yang
berisi Web Server NGINX dengan Modul tambahan
RTMP Stream dan RTMP Push Stream yang sudah saya
Compile dan Packaging Ulang menjadi siap install untuk 
tujuan membuat Server Streaming dengan Protokol RTMP.

## INSTRUKSI INSTALASI

Instalasi ini membutuhkan Koneksi Internet serta akses
Super User. Bisa dengan akun Root atau Perintah Sudo.

;; Instalasi Dependensi dari Modul NGINX

# apt-get install fontconfig-config fonts-dejavu-core 
libfontconfig1 libgd3 libhiredis0.13 libjbig0 libjpeg-turbo8 
libjpeg8 libluajit-5.1-2 libluajit-5.1-common libtiff5 libvpx3 
libxpm4 libxslt1.1

;; Instalasi Modul-modul NGINX
# dpkg -i nginx-common*.deb libnginx*.deb

;; Instalasi NGINX
# dpkg -i nginx-full*.deb