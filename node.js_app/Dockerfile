# Uses Node.js 18 image version
FROM node:18

# Creates and sets app directory
WORKDIR /usr/src/app

# Copies package.json and package-lock.json
COPY package*.json ./

# Installs dependencies
RUN npm install

# Copies application source code
COPY . .

# Exposes the app to port
EXPOSE 3000

# Starts the app
CMD ["npm", "start"]
