FROM node

ENV PORT=4000

WORKDIR /backend-app

COPY package.json .

RUN npm install

COPY . .

EXPOSE $PORT

ENV MONGODB_USERNAME=hieu
ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]
