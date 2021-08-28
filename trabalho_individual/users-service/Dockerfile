FROM node:13-alpine

WORKDIR /app

COPY . .

RUN yarn

CMD ["sh", "-c", "yarn db:migrate ; yarn watch"]

EXPOSE 7101