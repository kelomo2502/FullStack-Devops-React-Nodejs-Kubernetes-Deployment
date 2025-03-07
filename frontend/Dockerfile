# Dockerfile for React frontend

FROM node:18

# For frontend Dockerfile
WORKDIR /app
COPY frontend/package*.json ./
RUN npm install
COPY frontend/public ./public
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
