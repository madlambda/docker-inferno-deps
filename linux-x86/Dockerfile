FROM dockcross/linux-x86:latest
MAINTAINER Tiago Natel de Moura (tiago4orion@gmail.com)
ENV DEFAULT_DOCKCROSS_IMAGE madlambda/inferno-linux-x86-deps
RUN echo 'deb http://deb.debian.org/debian/ stable main contrib non-free' > /etc/apt/sources.list
RUN echo 'deb-src http://deb.debian.org/debian/ stable main contrib non-free' >> /etc/apt/sources.list
RUN echo 'deb http://deb.debian.org/debian/ stable-updates main contrib non-free' >> /etc/apt/sources.list
RUN echo 'deb-src http://deb.debian.org/debian/ stable-updates main contrib non-free' >> /etc/apt/sources.list
RUN apt-get update && apt-get -y install libx11-dev:i386 libxext-dev:i386
