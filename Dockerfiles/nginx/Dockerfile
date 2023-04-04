FROM ubuntu:18.04   
RUN  apt-get -y update && apt-get -y install nginx
COPY conf/etc/nginx/default /etc/nginx/sites-available/default
COPY ../../app/index.html /usr/share/nginx/html/index.html
#COPY files/default /etc/nginx/sites-available/default
#COPY files/index.html /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]

