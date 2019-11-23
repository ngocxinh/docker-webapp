FROM ubuntu:16.04
LABEL author="NgocVT3"
WORKDIR /root/backend
RUN apt update -y
RUN apt install curl -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
COPY . /root/backend/

RUN npm install
CMD FRONT_URL=${FRONT_URL} npm install
EXPOSE 8000


