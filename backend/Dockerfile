# Define base image
FROM node:19.2.0-alpine

# Define working directory
WORKDIR /app

# Copy package.json and package-lock.json to the working directory
COPY package*.json .

# Install dependencies
RUN npm install

# Copy rest of the app to the working directory
COPY . .

# Expose port 8001
EXPOSE 8001

# Define entry point
CMD ["npm", "start"]