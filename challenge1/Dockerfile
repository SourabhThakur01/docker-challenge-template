# Use the NGINX image from Docker Hub as the base image
FROM nginx:alpine

# Copy the 'public' directory contents into the container at /usr/share/nginx/html
# This is the default directory where NGINX serves files from
COPY public /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
