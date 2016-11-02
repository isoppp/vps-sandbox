# Base image
FROM ubuntu:latest

# Author
MAINTAINER hoge

# command when build
RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y curl
RUN touch /etc/apt/sources.list.d/nginx.list
RUN echo "deb http://nginx.org/packages/ubuntu/ precise nginx" >> /etc/apt/sources.list.d/nginx.list
RUN echo "deb-src http://nginx.org/packages/ubuntu/ precise nginx" >> /etc/apt/sources.list.d/nginx.list
RUN curl http://nginx.org/keys/nginx_signing.key | apt-key add -
RUN apt-get update
RUN apt-get install -y nginx

# Port
EXPOSE 22 80

# command when boot container
CMD ["echo", "running!"]
