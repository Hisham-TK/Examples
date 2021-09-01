# Select base image
FROM node:16.8.0-alpine3.13

# Set default path for all commands
WORKDIR /usr/app

# Install some dependancy
COPY package.json .
RUN npm i
COPY . .

# Startup command
CMD [ "npm", "start" ]