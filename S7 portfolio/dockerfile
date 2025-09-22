# Use the official Nginx image as base
FROM nginx:alpine

# Copy all your project files to the default Nginx html directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
