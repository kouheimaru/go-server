FROM golang:1.17.0-alpine3.14

WORKDIR /go_app

RUN ls
RUN pwd

COPY main.go /go_app

RUN apk update && apk add git

CMD go run main.go