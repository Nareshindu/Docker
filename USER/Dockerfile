FROM almalinux:9
RUN dnf install nginx -y
RUN useradd naresh
USER naresh
CMD ["nginx", "-g", "daemon off;"]