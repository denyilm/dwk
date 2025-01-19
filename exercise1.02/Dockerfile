FROM node:23

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=4500

EXPOSE $PORT

CMD ["npm", "start"]
