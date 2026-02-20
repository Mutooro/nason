# Nginx is the best choice for serving static HTML/CSS/JS sites
FROM nginx:alpine

# Remove the default Nginx placeholder page
RUN rm -rf /usr/share/nginx/html/*

# Copy all your project files into Nginx's serving directory
COPY . /usr/share/nginx/html/

# Expose port 80
EXPOSE 80