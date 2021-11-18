FROM node:12.22.6

WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . .
RUN mkdir /logs

CMD [ "npm", "start" ]
