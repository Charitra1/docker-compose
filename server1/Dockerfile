FROM centos
#RUN yum install httpd -y \
 #   systemctl start httpd 

#VOLUME ["/var/www/html/"]    
ADD . /var
WORKDIR /var
#COPY index.html /var/www/html/
#EXPOSE 80
CMD ["echo","Hello world"]

