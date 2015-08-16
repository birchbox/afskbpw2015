# Copyright (C) 2015 Birchbox Inc
# See LICENSE for details
FROM debian:jessie
MAINTAINER Thomas Kula <kula@birchbox.com>
LABEL Description="A base image with krb5-user installed"
RUN apt-get update
RUN DEBIAN_FRONTEND='noninteractive' apt-get install -y krb5-user
RUN useradd -m kula 

