# Use the official Nginx image as base
FROM nginx:alpine

# Remove default Nginx content
RUN rm -rf /usr/share/nginx/html/*

# Copy all contents of the "S7 portfolio" folder into Nginx html directory
COPY ./S7\ portfolio/* /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
