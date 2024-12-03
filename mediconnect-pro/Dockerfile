FROM node:16

# Set the working directory in the container
WORKDIR /app

# Copy package*.json files to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code to the working directory
COPY . .

# Expose the port your application listens on (e.g., 3000)
EXPOSE 5000

# Run the command to start your application
CMD ["node", "index.js"]