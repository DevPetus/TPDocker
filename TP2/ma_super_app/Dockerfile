FROM node:12-alpine3.9

WORKDIR /app

RUN npm install --production

COPY . /app/

CMD ["node", "src/index.js"]
