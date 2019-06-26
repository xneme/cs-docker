FROM node:10.15

WORKDIR /
COPY . .

RUN npm ci

EXPOSE 8000

CMD ["npm", "start"]