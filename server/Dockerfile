FROM node:18

WORKDIR /usr/src/app

COPY package*.json /usr/src/app/

RUN npm install

COPY ./ /usr/src/app/

RUN npm run build

EXPOSE 3000

CMD ["node", "dist/index.js"]