FROM ubuntu:14.04
MAINTAINER kiss5891@gmail.com
RUN apt-get update && apt-get -y upgrade
RUN curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
RUN apt-get install -y nodejs git npm
ADD . /ele
RUN cd /ele
RUN npm install process
CMD ["nodejs", "/ele/flowController/flow.js"]
