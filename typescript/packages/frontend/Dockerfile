FROM node:18.13-alpine

WORKDIR /app

COPY . .

RUN yarn @frontend install

CMD yarn @frontend dev
