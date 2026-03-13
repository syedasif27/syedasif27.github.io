FROM node:20-alpine
WORKDIR /app
COPY package.json .
RUN npm install --omit=dev
EXPOSE 3000
COPY server.js .
CMD ["node", "server.js"]

