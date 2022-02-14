FROM node:16-alpine

WORKDIR '/app'

ENV PATH="./node_modules/.bin:$PATH"

COPY ./package*.json .

RUN npm install

RUN npm install @angular/cli -g

COPY . .

EXPOSE 4200
EXPOSE 49153

CMD ["npm", "start"]