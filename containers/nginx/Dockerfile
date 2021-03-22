FROM nginx: 1.15.8

# Delete the directory for include 
RUN rm  -f /etc/nginx/conf.d/ *

# Copy Nginx configuration file to container 
ADD nginx.conf /etc/nginx/conf.d/webapp.conf

# Start Nginx after build is complete 
CMD / usr / sbin / nginx -g 'daemon off;' -c /etc/nginx/nginx.conf