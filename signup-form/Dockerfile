# Use Node.js image
FROM node:22

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy project files
COPY . .

# Expose Vite port
EXPOSE 5173

# Start the development server
CMD ["npm", "run", "dev", "--", "--host"]