FROM node:16.13.2-alpine
WORKDIR /usr/app
COPY package.json .
RUN npm install --quiet
COPY public .
