FROM alpine
WORKDIR /work
RUN export http_proxy="http://proxy:3128"
RUN export https_proxy="http://proxy:3128"
RUN apk update
RUN apk upgrade
RUN apk add nano
RUN apk add iputils
RUN apk add build-base
RUN apk add python3
