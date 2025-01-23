FROM nginx:stable
EXPOSE 80
COPY ./index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]

# docker run -p 80:80 --name my-nginx-container -d my-nginx