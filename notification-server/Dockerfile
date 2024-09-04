FROM node:22.8-alpine

WORKDIR /app

COPY package.json package-lock.json /app/

RUN npm install

COPY . /app/

EXPOSE 4040

CMD ["npm", "run", "start"]
