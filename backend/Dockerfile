FROM node:9.11-alpine

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

ADD . /usr/src/app/
RUN npm install

EXPOSE 9000

CMD [ "npm", "start" ]