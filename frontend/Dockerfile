FROM ubuntu:16.04
LABEL author="NgocVT3-FE"
WORKDIR /root/frontend
RUN apt update -y
RUN apt install curl -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
COPY . /root/frontend/

RUN npm install
EXPOSE 5000
CMD API_URL=${API_URL} npm install




