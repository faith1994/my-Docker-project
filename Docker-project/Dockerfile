FROM nginx
RUN apt-get update
RUN apt-get install -y nginx
COPY index.nginx.html var/www/html
CMD [ "nginx-g'daemon off,'" ]