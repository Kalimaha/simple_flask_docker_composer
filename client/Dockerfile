# Create a container from Ubuntu.
FROM ubuntu:14.04

# Credits.
MAINTAINER Guido Barbaglia "guido.barbaglia@gmail.com"

# Update Ubuntu repositories.
RUN apt-get update

# Install Apache.
RUN apt-get -y install apache2

# Install unzip.
RUN apt-get -y install wget
RUN apt-get -y install unzip

# Get and unzip sources.
RUN wget https://github.com/Kalimaha/simple_flask_ui/archive/master.zip
RUN unzip master.zip
RUN mv simple_flask_ui-master/ /var/www/html/simple_flask_ui