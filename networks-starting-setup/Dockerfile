FROM node

ARG DEFAULT_PORT=4000

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT $DEFAULT_PORT

EXPOSE $PORT

CMD ["node", "app.js"]