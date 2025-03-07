# Set the base image
FROM node:18

# Set the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy only necessary files
COPY public ./public
COPY src ./src

# Expose the React app port
EXPOSE 3000

# Start the application
CMD ["npm", "start"]
