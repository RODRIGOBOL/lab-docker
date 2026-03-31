FROM nginx:alpine
WORKDIR /usr/share/nginx/html
COPY . .
RUN chmod +x entrypoint.sh
ENTRYPOINT ["/bin/sh", "entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]
