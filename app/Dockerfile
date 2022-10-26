FROM node:latest

# Create app directory
WORKDIR "C:/Users/LChokHoe/Desktop/Uni Storage/Modules/Y3S1/CS3219/OTOT A1/app"

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where avilable (npm@5+)
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

EXPOSE 8080
CMD [ "npm", "start" ]
