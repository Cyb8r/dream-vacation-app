FROM node:10-alpine
WORKDIR /dream-vacation-app/
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3032
CMD [ "node", "start" ]
