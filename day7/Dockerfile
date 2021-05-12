FROM node:12.18.1

RUN mkdir day8
WORKDIR /day8

COPY server.js /day8/server.js

RUN npm install express &&\ 
npm install mysql

CMD [ "node", "server.js" ]
EXPOSE 3000
