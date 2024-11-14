FROM node:10-slim
WORKDIR /dream-vacation/
COPY public /dream-vacation/public
COPY src /dream-vacation/src
COPY package*.json ./
COPY . .
EXPOSE 3031
CMD [ "node", "start" ]
