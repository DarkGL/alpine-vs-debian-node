FROM node:20-bookworm

WORKDIR /usr/src/app

RUN apt update && apt install git bash

RUN git clone https://github.com/DarkGL/benchmarks.git

WORKDIR /usr/src/app/benchmarks

RUN npm install

CMD ["bash"]