FROM node:10-alpine

WORKDIR /usr/local/app

COPY package*.json ./

RUN npm install

COPY . .

#EXPOSE 9090
CMD ["npm", "start"]