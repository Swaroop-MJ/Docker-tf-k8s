#Base OS
FROM almalinux:8
#Installing or updating the required packages
RUN yum update -y
#Installing the nginx web server
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#Copying the application code
COPY hightech-html/ /usr/share/nginx/html
#Starting the web server
CMD ["nginx", "-g", "daemon off;"]