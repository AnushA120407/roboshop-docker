FROM node:20
WORKDIR /app
COPY package.json .
COPY *.js .
# node_modules
RUN npm install 
EXPOSE 8080
CMD ["node", "server.js"]