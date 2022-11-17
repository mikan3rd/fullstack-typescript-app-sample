FROM node:18.12-alpine

WORKDIR /app

COPY . .

RUN yarn @frontend install

CMD yarn @frontend dev
