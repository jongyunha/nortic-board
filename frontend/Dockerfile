FROM node:alpine

WORKDIR /usr/src/app/frontend

COPY package.json ./

RUN npm i

COPY ./ ./

CMD ["npm", "run", "start"]