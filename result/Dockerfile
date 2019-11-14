# Using official Node.js runtime base image
FROM node:10-slim

# Set the application directory

# Install nodemon
RUN npm install -g nodemon

# Copy our packages definitions


# Install node modules
RUN npm ci \
	&& npm cache clean --force \
	&& mv /app/node_modules /node_modules

# Copy our code from the current directory into the workdir


# Set requires environments


# Make port 80 available for links and/or publish


# Set default command to execute

