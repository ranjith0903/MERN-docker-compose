# Use Node.js 18.9.1 as the base image
FROM node:18.9.1

# Set the working directory inside the container
WORKDIR /app  

# Copy package.json to the working directory
COPY package.json .  

# Install dependencies
RUN npm install  

# Copy the entire backend code into the working directory
COPY . .  

# Expose port 5050 to allow external access
EXPOSE 5050  

# Command to start the backend
CMD ["npm", "start"]
