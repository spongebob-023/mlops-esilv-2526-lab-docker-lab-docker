FROM nginx:alpine 
WORKDIR /usr/share/nginx/html 
COPY . . 
RUN chmod +x entrypoint.sh 
ENTRYPOINT ["/usr/share/nginx/html/entrypoint.sh"] 
CMD ["nginx", "-g", "daemon off;"]
