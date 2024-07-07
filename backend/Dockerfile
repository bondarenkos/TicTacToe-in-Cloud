
FROM node:14

WORKDIR /projekt/backend

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "index.js"]
