FROM node:19-alpine
WORKDIR /app
COPY package.json .
COPY src .
# run linux shell command
RUN npm install 
# instruction to be executed when container starts
ENTRYPOINT [ "node","server.js"]