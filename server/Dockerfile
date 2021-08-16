FROM node:12.19.0-alpine3.9 As development

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm i

COPY . .

RUN npm run build
