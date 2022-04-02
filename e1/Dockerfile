FROM ubuntu:20.04

RUN apt update && apt -y install nginx

RUN echo "Hello world" >> /var/www/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
