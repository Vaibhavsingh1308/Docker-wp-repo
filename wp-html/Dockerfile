FROM wordpress:latest
WORKDIR /var/www/html
COPY html/ /var/www/html/
COPY Dockerfile /var/www/html
RUN chown -R www-data:www-data /var/www/html
EXPOSE 80
