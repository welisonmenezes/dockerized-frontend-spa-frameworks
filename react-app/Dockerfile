FROM node:16-alpine

WORKDIR '/app'

ENV PATH="./node_modules/.bin:$PATH"

COPY ./package*.json .

RUN npm install

COPY . .

EXPOSE 3000
EXPOSE 35729

CMD ["npm", "start"]