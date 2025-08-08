# Use official Node.js image
FROM node:18

# Create app directory
WORKDIR /usr/src/app

# Copy app files
COPY app/ ./app/
COPY package.json ./

# Install dependencies
RUN npm install

# Expose port
EXPOSE 3000

# Run app
CMD ["node", "app/index.js"]