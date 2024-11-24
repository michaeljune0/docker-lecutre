# base image
FROM alpine:latest

# nginx package add
RUN apk add nginx

# file copy
COPY nginx.conf /etc/nginx/nginx.conf
COPY 2048 /usr/share/nginx/html

# port 80
EXPOSE 80

# excute cmd
CMD ["nginx", "-g", "daemon off;"]
