FROM node:18.11.0
WORKDIR /home/app
COPY package*.json ./
RUN npm install # Aproveitando as camadas
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]