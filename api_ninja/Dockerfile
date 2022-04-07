FROM node:17-alpine

WORKDIR /app

COPY . .

RUN npm install

# required for docker desktop port mapping
EXPOSE 4000

CMD ["node", "app.js"]