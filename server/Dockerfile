FROM golang

MAINTAINER Simon Critchley

ADD . /go/src/code.avct.io/server
WORKDIR /go/src/code.avct.io/server

RUN go install code.avct.io/server

ENTRYPOINT /go/bin/server

EXPOSE 5000
