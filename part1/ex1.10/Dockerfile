FROM node:10.15

WORKDIR /mydir
COPY . .

RUN npm ci

EXPOSE 5000

CMD ["npm", "start"]