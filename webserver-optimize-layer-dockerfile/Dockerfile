FROM ubuntu:latest
MAINTAINER piyushkumar13
RUN apt-get update \
    && apt-get install -y \
    apache2 \
    apache2-utils \
    vim \
    && apt-get clean
EXPOSE 80
CMD ["apache2ctl", "-D", "FOREGROUND"]