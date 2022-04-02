FROM ubuntu:20.04

RUN apt update && apt install -y curl
RUN curl -sL https://deb.nodesource.com/setup_16.x | bash -
RUN apt install -y nodejs

COPY . .

EXPOSE 3000

CMD ["node", "server.js"]
