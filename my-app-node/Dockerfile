FROM node:latest
COPY index.js /home/app/index.js
COPY package.json /home/app/package.json
# COPY . /home/app  not recommended as it copy the node_modules directory files too

WORKDIR /home/app/

RUN npm install

EXPOSE 9000

CMD [ "node","index" ]