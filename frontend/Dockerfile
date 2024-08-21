FROM node:20-alpine

RUN mkdir /app
WORKDIR /app

COPY ./frontend/package.json /app/
COPY ./frontend/package-lock.json /app/

RUN npm install

COPY . /app/


EXPOSE 3000
CMD ["npm", "start"]
