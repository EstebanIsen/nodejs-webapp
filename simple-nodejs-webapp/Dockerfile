FROM node:14

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

ENV APPLICATION_INSTANCE=example

CMD ["node", "src/count-server.js"]
