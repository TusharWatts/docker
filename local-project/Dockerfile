FROM node

WORKDIR ./home/my-server

COPY . .

EXPOSE 3000

RUN npm ci

CMD ["npm", "start"]