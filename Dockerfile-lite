# Use a Node.js base image
FROM node:19-alpine

# Create a directory for your app
WORKDIR /usr/app

# Copy your application code to the container
COPY . /usr/app/

# Install app dependencies
RUN npm install

# Run tests using Mocha
CMD ["npm", "test"]

# Define the entry point for your container
ENTRYPOINT ["node", "server.js"]