# Use an official nginx image
FROM nginx:alpine

# Copy static assets from Vue build
COPY /dist /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx when the container has provisioned
CMD ["nginx", "-g", "daemon off;"]
