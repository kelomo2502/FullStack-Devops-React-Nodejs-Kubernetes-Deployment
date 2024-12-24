# Dockerfile for React frontend

FROM node:16-alpine

# For frontend Dockerfile
WORKDIR /app
COPY frontend/package*.json ./
RUN npm install
COPY frontend/public ./public
COPY frontend/. .
EXPOSE 3000
CMD ["npm", "start"]
