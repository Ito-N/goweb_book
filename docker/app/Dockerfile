FROM golang:1.15-alpine

RUN apk add --no-cache git

# コンテナの作業ディレクトリを変更
RUN mkdir /go/src/app
WORKDIR /go/src/app
ADD ./ /go/src/app