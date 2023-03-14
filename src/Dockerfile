FROM node:18.13.0

WORKDIR /usr/src/app

COPY . .

RUN npm ci --only=production

RUN npm run build

CMD ["npm","start"]