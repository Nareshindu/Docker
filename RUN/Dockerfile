FROM almalinux:9 
RUN echo "hello world"
RUN dnf install nginx -y
 RUN useradd naresh
COPY naresh.txt /tmp/naresh.txt
ADD apache-tomcat-9.0.90.tar.gz /tmp
ADD https://github.com/Nareshindu/ansible/blob/main/01-ping.yaml /tmp
LABEL multi.label1="value1" \
      multi.label2="value2" \
      other="value3"
CMD ["nginx", "-g", "daemon off;"]
USER naresh
