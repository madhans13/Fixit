FROM node:18-alpine

WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy project files
COPY . .

# Create uploads directory
RUN mkdir -p uploads

EXPOSE 5000

CMD ["npm", "run", "dev"] 