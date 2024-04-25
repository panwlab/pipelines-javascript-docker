# syntax=docker/dockerfile:1

# FROM node:12.18.1
# FROM node:16.13.2
# FROM node:20.8.0
# FROM node:21.2.0
FROM ubuntu/apache2:latest

# ENV NODE_ENV=production

# WORKDIR /app

# COPY ["package.json", "package-lock.json*", "./"]

# RUN npm install --production
RUN apt-get update && apt-get install -y iputils-ping
RUN apt-get install -y curl
RUN apt-get install -y net-tools
RUN apt-get install -y nmap 

# COPY . .

EXPOSE 8080
# CMD [ "node", "server.js" ]
