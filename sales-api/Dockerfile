FROM node:18.13.0
WORKDIR .
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8083
CMD ["node", "app.js"]
