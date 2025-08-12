FROM nginx
WORKDIR /var/app
COPY /docker/nginx/default.conf /etc/nginx/conf.d/
EXPOSE 8000
CMD ["nginx", "-g", "daemon off;"]
