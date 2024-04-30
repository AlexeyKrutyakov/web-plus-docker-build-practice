FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY package*.json /home/ilovedocker/app/
RUN npm i --omit=dev
COPY ./task3/src/. /home/ilovedocker/app/
EXPOSE 3032
CMD [ "node", "main.js" ]