FROM node:14.14.0-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install -g npm@8.6.0
COPY . .
CMD ["npm","run","start"]