FROM node:alpine

WORKDIR /usr/src/app

COPY package.json /usr/src/app
RUN npm install
COPY main.js /usr/src/app

CMD ["npm", "start"]