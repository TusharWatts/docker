FROM node

RUN npm install -g nodemon

WORKDIR /app

COPY package*.json .

RUN npm ci && mv /app/node_modules    /node_modules

COPY . .

CMD ["npm", "start"]