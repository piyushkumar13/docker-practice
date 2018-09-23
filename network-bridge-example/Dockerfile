FROM ubuntu:latest
MAINTAINER piyushkumar13
RUN apt-get update && apt-get install -y iputils-ping traceroute apache2
EXPOSE 80
CMD [ "-D","FOREGROUND" ]
ENTRYPOINT [ "apache2ctl" ]