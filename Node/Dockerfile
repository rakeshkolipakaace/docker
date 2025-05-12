FROM node:latest

WORKDIR /app

# Copy package.json and package-lock.json first (to cache npm install step)
COPY package*.json ./

# Install dependencies
RUN npm install

# Now copy the rest of the source code
COPY . .

# Run the app
CMD ["node", "app.js"]
