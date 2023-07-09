#FROM should be the first instruction always but only one exception is you can have ARG before FROM 
#but this Value is valid till FROM statement only.
#Diff between arg and env
#ENV variables are accessed bith in image and container
#ARG is only accessible at the time of image creation. it is not accessible from container.
ARG VERSION
FROM almalinux:${VERSION}
ARG GREETING
RUN echo "${GREETING}"