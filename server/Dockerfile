FROM node:18-alpine3.15
COPY . .
RUN ["rm", "-f", "./usr/share/nginx/html/Dockerfile"]
EXPOSE 3000
ENTRYPOINT ["node", "./api.js"]