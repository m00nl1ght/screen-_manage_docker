FROM node:lts-alpine

COPY . /app

WORKDIR /app/html

RUN npm install
RUN apk add --no-cache bash

EXPOSE 8080

CMD ["npm", "run", "serve"]