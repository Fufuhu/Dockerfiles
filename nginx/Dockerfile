FROM nginx:1.21-alpine

COPY conf.d/default.conf /etc/nginx/conf.d/default.conf
COPY html/test.html /usr/share/nginx/html/test.html
RUN chmod 644 /usr/share/nginx/html/test.html