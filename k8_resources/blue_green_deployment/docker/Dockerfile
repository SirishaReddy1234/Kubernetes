# Use an official Nginx image
FROM nginx:alpine

# Copy the index.html file to the Nginx document root
COPY green_deploy.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Run Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]