FROM node:lts-alpine

WORKDIR /app

# Copy package files FIRST
COPY package*.json ./  

RUN npm install --omit=dev  

COPY . .  

EXPOSE 5173

CMD ["npm", "run", "dev"] 