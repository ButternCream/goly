FROM node:18-alpine AS build

WORKDIR /app

EXPOSE 7321

COPY package.json ./
# COPY yarn.lock ./
RUN yarn install

COPY . ./
CMD ["yarn", "run", "dev"]

