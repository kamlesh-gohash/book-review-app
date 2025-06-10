FROM node:20

WORKDIR /app

COPY package.json ./
COPY package-lock.json ./
RUN npm install

# ✅ Copy public folder
COPY public/ ./public/

# ✅ Copy source code
COPY src/ ./src/

EXPOSE 3000
CMD ["npm", "start"]
