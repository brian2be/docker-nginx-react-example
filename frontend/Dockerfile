# Step 1: Build process
FROM node:10.16.2 as build-deps
WORKDIR /usr/src/app
COPY package.json yarn.lock ./
RUN yarn
COPY . ./

CMD ["yarn", "start"]