FROM node:20-slim

WORKDIR /app

COPY package*.json /app/

RUN npm i --force

COPY . .

EXPOSE 5173

CMD ["npm","run","dev"]