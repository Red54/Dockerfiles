FROM debian:8
MAINTAINER 谢致邦 <Yeking@Red54.com>
RUN echo 'APT::Install-Recommends "0";' > /etc/apt/apt.conf.d/99norecommends
RUN apt-get update && apt-get upgrade -y && apt-get dist-upgrade -y
RUN apt-get install -y git colordiff
