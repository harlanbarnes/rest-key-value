FROM node:alpine

# Create app directory
WORKDIR /app
# copy all files to App folder

COPY . .
# install dependency in package.json

RUN npm install

EXPOSE 3000
CMD [ "node", "server.js" ]
