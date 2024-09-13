# Use Nginx to serve static files
FROM nginx:stable-alpine

# Copy all the files to the Nginx html directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
