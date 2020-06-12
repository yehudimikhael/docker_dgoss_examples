FROM node:14.4.0-stretch

WORKDIR /usr/src/app

COPY package.json ./

RUN npm install

COPY . . 

EXPOSE 8080

CMD ["node", "server.js"]