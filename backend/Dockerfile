# Use node image
FROM node:14

# Set the working directory in the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the application files
COPY . .

# Expose port 5000 for the backend
EXPOSE 5000

# Command to start the backend
CMD ["npm", "start"]
