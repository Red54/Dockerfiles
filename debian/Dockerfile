FROM debian
MAINTAINER 谢致邦 <Yeking@Red54.com>
COPY apt /etc/apt
RUN apt-get update && apt-get install -y \
	apt-file \
	bzip2 \
	colordiff \
	deborphan \
	file \
	g++ \
	gawk \
	git \
	libncurses5-dev \
	make \
	openssh-client \
	openssl \
	python \
	quilt \
	unzip \
	vim \
	zlib1g-dev \
&& apt-get clean \
&& rm -rf /var/lib/apt/lists/*
