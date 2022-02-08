FROM node:lts-alpine

COPY  ./app/. /app/

WORKDIR /app

# RUN npm install
RUN apk add --no-cache bash

EXPOSE 8080

# CMD ["npm", "run", "serve"]