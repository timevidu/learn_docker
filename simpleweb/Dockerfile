#specify base image
FROM node:14-alpine

WORKDIR /usr/app
#install some dependencies
Copy ./ ./
RUN npm install

#Default command
CMD ["npm", "start"]



