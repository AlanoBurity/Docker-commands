FROM node:14-alpine

WORKDIR /front-end

COPY package*.json ./

ADD node_modules.tar.gz .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]