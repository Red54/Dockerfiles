FROM debian
MAINTAINER 谢致邦 <Yeking@Red54.com>
COPY apt /etc/apt
RUN apt-get update && apt-get install -y \
	apt-file \
	ca-certificates \
	colordiff \
	deborphan \
	dnsutils \
	file \
	g++ \
	gawk \
	git \
	less \
	libncurses5-dev \
	libssl-dev \
	make \
	man-db \
	net-tools \
	openssh-client \
	proxychains \
	psmisc \
	python \
	quilt \
	sharutils \
	subversion \
	unzip \
	vim \
	wget \
	xz-utils \
&& apt-file update
