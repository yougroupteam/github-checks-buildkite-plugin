FROM alpine:3.8
RUN apk add --no-cache python3=3.6.9-r1 py3-cryptography=2.1.4-r1 bash build-base python3-dev
COPY . /ghapp
RUN pip3 install /ghapp
