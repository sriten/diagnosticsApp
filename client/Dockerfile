# Use an official Python runtime as a parent image
FROM node:12.6.0

ENV PORT=3000
ENV DB_NAME=propbet
ENV ACCOUNTS_SECRET=secret
ENV MONGO_HOST=0.0.0.0

WORKDIR /usr/src/app

COPY . .

RUN yarn

EXPOSE 3000

CMD ["yarn", "start"]