# Use an official web server image as the base image
FROM nginx:latest

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Copy the entire directory to the container
COPY . .

# Expose port 80 for the web server
EXPOSE 80

# Start the nginx web server when the container runs
CMD ["nginx", "-g", "daemon off;"]







