#Use existing docker image as a base
FROM node:alpine
#Setting working directory
WORKDIR /usr/app
#Copy package.json
COPY ./package.json ./
#Install necessary dependencies
RUN npm install 
#Copy other files
COPY ./ ./
#Specify default command
CMD ["npm", "start"]