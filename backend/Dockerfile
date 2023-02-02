FROM node:14-slim

WORKDIR ./src

COPY ./package.json ./


RUN npm i
RUN npm update


BASE_URL=http://localhost:3000






EXPOSE 8000

CMD [ "npm", "start" ]
