FROM node:14
WORKDIR node:14
COPY package.json .
RUN npm install
COPY ..
EXPOSE 8080
CMD ["node", "app.js"]