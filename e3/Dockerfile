FROM ubuntu:20.04

RUN apt update && apt install -y nginx

ADD my-app /var/www/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
