FROM node:18.15-alpine

WORKDIR /app

COPY ./frontend/package.json ./
COPY ./frontend/package-lock.json ./

RUN npm install

EXPOSE 8081

CMD [ "npm", "start" ]