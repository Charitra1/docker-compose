FROM centos
RUN yum install httpd -y \
    systemctl start httpd
ADD index.html /var/www/html/
EXPOSE 80
#CMD netstat -antp

