FROM node:14-slim

WORKDIR ./src

COPY ./package.json ./


RUN npm i
RUN npm update



EXPOSE 8000

CMD [ "npm", "start" ]
