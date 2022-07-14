FROM node:18

WORKDIR /app/api

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 2022

CMD ["npm", "run", "backend"]