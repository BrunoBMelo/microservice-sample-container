FROM node:latest
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8181
CMD ["server.js"]
