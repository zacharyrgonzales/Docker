#Grab centos image from dockerhub
FROM centos

#run yum package manager in shell
RUN yum install httpd -y

#add and extract tar fil in apache html dir.
ADD ./file.tar.gz /var/www/html

#start web server
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]

#expose port 80
EXPOSE 80