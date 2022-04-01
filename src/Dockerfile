FROM node:14.18.1

WORKDIR /usr/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8081

CMD ["npm", "start"]