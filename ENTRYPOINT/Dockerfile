FROM almalinux:8
#CMD command can be overriden
#ENTRYPOINT cannot be overriden, instead it will go and append
#if you use both CMD and ENTRYPOINT, CMD will provide arguments to the ENTRYPOINT
#CMD is used to provide default arguments to the ENTRYPOINT, but you can always override CMD from command line
#you are restricting users not to run some commands on their own. they can only provide args to the command.
CMD [ "google.com" ]
ENTRYPOINT [ "ping", "-c5" ]