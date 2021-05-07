FROM node:12.18.1

RUN mkdir task6
WORKDIR /task6

COPY server.js /task6/server.js

RUN npm install express

CMD [ "node", "server.js" ]
EXPOSE 3000
