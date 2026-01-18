# Use official Node.js image
FROM node:20-alpine

# Set working directory
WORKDIR /usr/src/app

# Copy package files
COPY app/package*.json ./

# Install dependencies
RUN npm install --production

# Copy app source
COPY app/ .

# Expose application port
EXPOSE 3000

# Start the app
CMD ["npm", "start"]
