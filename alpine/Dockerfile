FROM node:20-alpine

WORKDIR /usr/src/app

RUN apk update && apk add --no-cache git bash

RUN git clone https://github.com/DarkGL/benchmarks.git

WORKDIR /usr/src/app/benchmarks

RUN npm install

CMD ["bash"]