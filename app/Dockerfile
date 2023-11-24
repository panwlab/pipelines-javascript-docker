# syntax=docker/dockerfile:1

# FROM node:12.18.1
# FROM node:16.13.2
FROM node:20.8.0
# FROM node:21.2.0
ENV NODE_ENV=production

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install --production

COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
