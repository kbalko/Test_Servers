FROM alpine:latest
RUN apk --no-cache upgrade && apk add --no-cache apache2
WORKDIR /var/www/localhost/htdocs
COPY  html  /var/www/localhost/htdocs 
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]




