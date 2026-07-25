FROM node:20
# creates /app and set the directory to /app
WORKDIR /app
COPY package.json .
COPY *.js .
# node_modules
RUN npm install 
EXPOSE 8080
CMD ["node", "server.js"]