FROM node:18.12-alpine

WORKDIR /app

COPY . .

RUN yarn @backend install

CMD yarn @backend start:dev
