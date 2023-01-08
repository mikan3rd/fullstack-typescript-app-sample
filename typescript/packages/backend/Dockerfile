FROM node:18.13-alpine

WORKDIR /app

COPY . .

RUN yarn @backend install

CMD yarn @backend start:dev
