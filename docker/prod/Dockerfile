FROM nginx:alpine
COPY . /usr/share/nginx/html
COPY docker/prod/nginx.conf /etc/nginx/conf.d/default.conf
RUN chmod -R 755 /usr/share/nginx/html

EXPOSE 80