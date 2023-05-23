FROM alpine
WORKDIR /work
env http_proxy=http://proxy:3128
env https_proxy=http://proxy:3128
RUN apk update
RUN apk upgrade
RUN apk add nano
RUN apk add iputils
RUN apk add python3
