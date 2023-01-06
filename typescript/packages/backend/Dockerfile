FROM node:19.1-alpine

WORKDIR /app

COPY . .

RUN yarn @backend install

CMD yarn @backend start:dev
