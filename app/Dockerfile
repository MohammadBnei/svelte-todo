FROM node:13

RUN apt-get update

WORKDIR /usr/src/app

COPY ["package.json", "package-lock.json", "./"]

RUN npm i --silent

CMD npm run dev