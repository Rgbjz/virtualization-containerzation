From ubuntu:latest

RUN apt-get update && \
    apt-get install -y apache2

RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf

CMD ["apache2ctl","-D", "FOREGROUND"]
