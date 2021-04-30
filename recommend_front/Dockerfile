# syntax=docker/dockerfile:1
FROM node:16-alpine3.11
WORKDIR /code
COPY . .
RUN npm config set registry https://registry.npm.taobao.org
RUN npm install -g @vue/cli
RUN npm install
CMD [ "npm", "run", "serve" ]