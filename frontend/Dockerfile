FROM node:14

WORKDIR /usr/src/src

COPY . ./


RUN npm i
RUN npm update


EXPOSE 3000

CMD [ "npm", "start" ]
