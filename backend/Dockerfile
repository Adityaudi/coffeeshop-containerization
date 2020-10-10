FROM node:lts-alpine

RUN mkdir -p /usr/src/backend

WORKDIR /usr/src/backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4040

CMD [ "node", "app.js" ]