FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
ADD https://github.com/Maheswari-Sanivarapu /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]