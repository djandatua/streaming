# streaming
RTMP Nginx Streaming Server
------------------------------
apt-get install fontconfig-config fonts-dejavu-core libfontconfig1 libgd3 libhiredis0.13 libjbig0 libjpeg-turbo8 libjpeg8 libluajit-5.1-2 libluajit-5.1-common libtiff5 libvpx3 libxpm4 libxslt1.1
dpkg -i nginx-common*.deb libnginx*.deb nginx-full*.deb
nano /etc/nginx/nginx.conf
rtmp_auto_push on;
 rtmp {
  server {
  listen 1935;
  application stream {
   live on;
   record off;
   }
  }
 }
