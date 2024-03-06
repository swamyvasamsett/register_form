FROM centos:centos7
RUN yum install update -y
RUN yum install httpd -y
CMD ["/USR/SBIN/HTTPD", "-D", "FOREGROUND"]
COPY . /var/www/html
