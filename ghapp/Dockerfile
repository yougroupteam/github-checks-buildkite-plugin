FROM alpine:3.8
RUN apk add --no-cache python3=3.6.8-r0 py3-cryptography bash
COPY . /ghapp
RUN pip3 install /ghapp