Docker container that runs a simple "hello world" application dockerfile
**********************************************************************************

FROM ubuntu:20.04
RUN apt update && apt install -y sbcl
WORKDIR /usr/src

commands to imlement
#docker build -t myimage .
#docker run -it --name container1  myimage /bin/bash



