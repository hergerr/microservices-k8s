FROM node:16-alpine

ENV CI=true

WORKDIR /app
COPY package.json /app
RUN npm install
COPY ./ ./

CMD ["npm", "start"]