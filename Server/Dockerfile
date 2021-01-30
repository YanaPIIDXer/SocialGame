FROM golang:latest

RUN go get -u \
    github.com/oxequa/realize \
    github.com/jinzhu/gorm

WORKDIR /go/src/server
ADD ./src /go/src/server

CMD realize start
