FROM node:12.18.1

RUN mkdir task6
WORKDIR /task6
COPY server.js /task6/server.js

RUN npm config set registry http://registry.npmjs.org/ && npm config set strict-ssl false && npm install express

CMD [ "node", "server.js" ]

EXPOSE 3000
