FROM centos:latest

RUN yum install httpd -y

RUN echo welcome > /var/www/html/index.html

EXPOSE 80

CMD ["/usr/sbin/httpd","-DFOREGROUND"]

