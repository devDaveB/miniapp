FROM nginx:1.23.0-alpine
COPY default.conf ./etc/nginx/conf.d/default.conf
RUN ["rm", "-f", "./usr/share/nginx/html/Dockerfile"]