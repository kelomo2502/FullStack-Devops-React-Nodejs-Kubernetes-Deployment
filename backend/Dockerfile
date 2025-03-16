FROM node:18

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the entire backend directory (excluding files from .dockerignore)
COPY . .

# Expose the application port
EXPOSE 5000

# Start the server
CMD ["npm", "start"]
