FROM node:16-alpine

WORKDIR '/app'

ENV PATH="./node_modules/.bin:$PATH"

COPY ./package*.json .

RUN npm install

COPY . .

EXPOSE 8080

CMD ["npm", "run", "serve"]