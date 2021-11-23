# Runing

 docker run -it --name my-apache-app -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4
 
# Browse to:

http://127.0.0.1:8080/index.html
