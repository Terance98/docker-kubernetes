FROM node

# set the present working directory to /app. All the subseuquent commands will be executed in this particular directory
WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

CMD ["node", "server.js"]

