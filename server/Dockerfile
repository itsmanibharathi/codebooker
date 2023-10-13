FROM node:14-alpine
WORKDIR /server
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3001

CMD ["sh", "-c", "npm run mongosetup && npm start"]