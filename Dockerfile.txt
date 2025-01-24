From node:22
WORKDIR /app
Copy package*.json ./
Run npm install
COPY ..
EXPOSE 3000
CMD ["npm", "start"]
