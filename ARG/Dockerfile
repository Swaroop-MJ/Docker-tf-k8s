#FROM should be the first instruction always but only one exception is you can have ARG before FROM 
#but this Value is valid till FROM statement only.
#Diff between arg and env
#ENV variables are accessed bith in image and container
#ARG is only accessible at the time of image creation. it is not accessible from container.
#docker build --build-arg VERSION=8 --build-arg GREETING=Hello -t arg:v1 .
#Now i have a ARG variable, i want to access this in container also -- then we have ENV instruction, create a ENV variable and assign the value of ARG to ENV variable
ARG VERSION
FROM almalinux:${VERSION}
ARG GREETING
ENV GREET=${GREETING}
RUN echo "${GREETING}"