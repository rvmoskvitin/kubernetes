FROM amazonlinux:2018.03.0.20191219.0
RUN yum -y update
RUN yum -y install httpd
RUN yum -y install php
COPY ./index.php /var/www/html/index.php
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
