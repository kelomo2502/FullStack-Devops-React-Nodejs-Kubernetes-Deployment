FROM node:16-alpine
# WORKDIR /app
# COPY package*.json ./
# RUN npm install
# COPY . .
# EXPOSE 5000
# CMD ["node", "server.js"]
WORKDIR /app
COPY backend/package*.json ./
RUN npm install
COPY backend/. .
EXPOSE 5000
CMD ["npm", "start"]
