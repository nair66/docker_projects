FROM node

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

ARG DEFAULT_PORT=80

EXPOSE $DEFAULT_PORT

CMD [ "npm", "start" ]

