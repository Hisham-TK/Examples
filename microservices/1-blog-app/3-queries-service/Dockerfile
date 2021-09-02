FROM node:16.8.0-alpine3.13

WORKDIR /usr/app

COPY package.json .
RUN npm i
COPY . .

CMD ["npm", "start"]