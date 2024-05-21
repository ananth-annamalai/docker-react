# specify base image
FROM node:14-alpine

# set the working folder
WORKDIR /usr/app

# Run Dependencies
COPY ./package.json ./
RUN npm install

COPY ./ ./

# Entry Command
CMD [ "npm", "start" ]
