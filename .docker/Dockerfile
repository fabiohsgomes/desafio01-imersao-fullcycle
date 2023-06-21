FROM golang:1.20.5-alpine

WORKDIR /opt/golang-app/

COPY ../cmd/desafio01.go /opt/golang-app/desafio01.go

RUN go build desafio01.go \
    && rm desafio01.go

CMD [ "./desafio01" ]