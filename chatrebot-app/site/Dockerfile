# Use official NGINX image
FROM nginx:alpine

# Copy static files to NGINX html directory
COPY site /usr/share/nginx/html

# Expose port 80 for web traffic
EXPOSE 80

# Start NGINX automatically
CMD ["nginx", "-g", "daemon off;"]
