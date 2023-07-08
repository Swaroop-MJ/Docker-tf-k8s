FROM almalinux:8
RUN yum update -y
RUN yum install nginx -yum
CMD ["nginx","-g","daemon off;"]
EXPOSE 80/tcp