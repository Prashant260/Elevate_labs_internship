FROM node:18

WORKDIR /nodejsapp

COPY package.json ./
RUN npm install

COPY . .

EXPOSE 3000
CMD ["npm", "start"]
