FROM node

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

VOLUME [ "/app/feedback"]

ARG DEFAULT_PORT=80

ENV PORT $DEFAULT_PORT

EXPOSE $PORT

CMD [ "npm", "start" ]

