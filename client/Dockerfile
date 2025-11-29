# Use nginx to serve the React app
FROM nginx:alpine

# Copy the build files to nginx html directory
COPY build /usr/share/nginx/html

# Copy custom nginx configuration if needed (optional)
# COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80
EXPOSE 80

# Start nginx
