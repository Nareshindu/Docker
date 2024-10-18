FROM almalinux:9 
RUN echo "hello world"
RUN dnf install nginx -y
LABEL multi.label1="value1" \
      multi.label2="value2" \
      other="value3"
CMD ["nginx", "-g", "daemon off;"]
