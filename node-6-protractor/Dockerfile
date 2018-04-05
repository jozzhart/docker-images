FROM node:6-alpine
MAINTAINER jozzhart <me@jozzhart.com>

RUN npm install protractor -g

EXPOSE 8000

WORKDIR /protractor

ENTRYPOINT ["protractor"]
