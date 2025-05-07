FROM almalinux:9
RUN dnf install nginx -ynginx/html/index.html
RUN rm -rf /usr/share/
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
