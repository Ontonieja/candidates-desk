FROM node:20-alpine

WORKDIR /client

COPY package.json yarn.lock ./
RUN yarn install

COPY . .


EXPOSE 5173
CMD ["yarn", "dev"]