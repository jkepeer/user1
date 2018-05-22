FROM nginx
COPY conf/nginx.conf /etc/nginx/nginx.conf
RUN mkdir -p /var/www/app
COPY www/index.html /var/www/app/index.html
RUN chown -R www-data:www-data /var/www/app
