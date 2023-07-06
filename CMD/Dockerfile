#To Install the Base OS
FROM almalinux:8
#To Update the Packages
RUN yum update -y
#To install nginx web server
RUN yum install nginx -y
#Command to run the nginx container in foreground
CMD ["nginx", "-g", "daemon off;"]

#RUN instruction will be executed at the time of image creation
#CMD instruction will be executed at the time of container creation