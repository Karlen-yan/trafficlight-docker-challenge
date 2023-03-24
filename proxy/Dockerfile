FROM nginx:latest

# COPY default.conf /etc/nginx/conf.d/
COPY default.conf ./
# COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]