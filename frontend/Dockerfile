FROM node:14-slim

WORKDIR /usr/src/app

COPY . ./


RUN npm i
RUN npm update


EXPOSE 3000

CMD [ "npm", "start" ]
