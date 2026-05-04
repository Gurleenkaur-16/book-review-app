FROM node:18-alpine

WORKDIR /app

COPY package*.json /app

RUN npm install

copy . .

EXPOSE 3001

CMD ["node","src/server.js"]

