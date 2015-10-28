FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY sites-enabled/static_site /etc/nginx/conf.d/default.conf

EXPOSE 80
