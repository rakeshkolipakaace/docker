FROM node

ENV MONOGO_DB_USERNAME=admin \
 MONGO_BD_PWD=qwerty



RUN mkdir -p docker-testapp

COPY . /docker-testapp

CMD ["node", "docker-testapp/server.js"]

