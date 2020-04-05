FROM node:12.13-alpine

WORKDIR /app

RUN apk update && npm i -g npm

RUN npm i apollo-server graphql

EXPOSE 4000

CMD ["/bin/sh"]