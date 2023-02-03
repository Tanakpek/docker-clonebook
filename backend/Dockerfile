FROM node:14-slim

WORKDIR /usr/src/src
COPY . ./



RUN npm i
RUN npm update



EXPOSE 8000

CMD [ "npm", "start" ]
