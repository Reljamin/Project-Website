FROM nginx:alpine
COPY nginx.conf /etc/nginx/nginx.conf
WORKDIR /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]

# command to build container
# docker build -t website .

# command to run container
# docker run -p 8080:80 -v $(pwd):/usr/share/nginx/html my-website

# http://localhost:8080