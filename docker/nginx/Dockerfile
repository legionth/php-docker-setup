FROM nginx:alpine

RUN apk update

RUN apk add --update nodejs nodejs-npm yarn

RUN npm install --no-bin
RUN /var/www/project/node_modules/.bin/encore dev-server

COPY / /var/www/project
WORKDIR /var/www/project

EXPOSE 80