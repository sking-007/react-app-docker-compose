
FROM node:16


WORKDIR /app


COPY package.json package-lock.json* ./


RUN yarn install


COPY . .


EXPOSE 5000

CMD ["yarn", "start"]

