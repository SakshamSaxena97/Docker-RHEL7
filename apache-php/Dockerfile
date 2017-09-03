FROM centos:latest

RUN yum install net-tools httpd php -y

COPY index.php /var/www/html

EXPOSE 80

CMD ["/usr/sbin/httpd","-DFOREGROUND"]

