FROM node:14.16.1-alpine

WORKDIR /usr/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000

#CMD ["npm", "start"]
