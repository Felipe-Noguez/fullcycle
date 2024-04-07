FROM node:latest

WORKDIR /usr/src/app

RUN npm init -y && npm install express && npm install mysql --save
# Comentários não funcionaram, mas deixo para estudo posterior
# ENV DOCKERIZE_VERSION v0.7.0

# RUN apt-get update \
#     && apt-get install -y wget \
#     && wget -O - https://github.com/jwilder/dockerize/releases/download/$DOCKERIZE_VERSION/dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz | tar xzf - -C /usr/local/bin \
#     && apt-get autoremove -yqq --purge wget && rm -rf /var/lib/apt/lists/*

# ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh /wait-for-it.sh
# RUN chmod +x /wait-for-it.sh
    
COPY . .

CMD [ "node", "index.js" ]