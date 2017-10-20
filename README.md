# Docker-RHEL/Centos

Repository contains Dockerfile to build various container images based on Redhat/ Centos.

# Check if Docker is installed or not
 
 $ rpm -q docker-engine
 
 $ yum install docker-engine
 
 $ systemctl restart docker

# Apache Dockerfile

$ docker build -t /apache

$ docker run -d -p 80:80 apache /usr/sbin/httpd -DFOREGROUND

Open web browser - localhost:80

<h3>Follow the same steps for other Dockerfiles as well   <h3>

