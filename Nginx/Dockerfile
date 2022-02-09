FROM nginx:latest

RUN mkdir /var/www
COPY ./conf/nginx.conf /etc/nginx/conf.d/nginx.conf

EXPOSE 2000
VOLUME /var/www
