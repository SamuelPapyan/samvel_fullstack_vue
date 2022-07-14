FROM node:10

WORKDIR /app/api

COPY package*.json ./

RUN npm install

EXPOSE 2022

CMD ["npm", "run", "backend"]