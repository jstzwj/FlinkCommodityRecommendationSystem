# syntax=docker/dockerfile:1
FROM node:16-alpine3.11
WORKDIR /code
COPY . .
RUN npm install -g @vue/cli
RUN npm install
RUN npm run serve