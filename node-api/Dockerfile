FROM node:lts-bullseye
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install --omit=dev
COPY . .
EXPOSE 80
CMD [ "node", "index.js" ]
