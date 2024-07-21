FROM python:3.13.0b3

MAINTAINER NGINX Docker Maintainers "docker-maint@nginx.com"

# Set the debconf front end to Noninteractive
RUN echo 'debconf debconf/frontend select Noninteractive' | debconf-set-selections && \
    	apt-get update && apt-get install -y -q \
	apt-transport-https \
	libffi-dev \
	libssl-dev \
	lsb-release \
	wget && \
    	cd /

