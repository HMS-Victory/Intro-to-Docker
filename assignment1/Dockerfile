FROM node:19-alpine

COPY package.json /app/
COPY src /app/

WORKDIR /app

RUN npm install

CMD ["node", "server.js"]

# Learn more here
# https://docs.docker.com/engine/reference/builder/