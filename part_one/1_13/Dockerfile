FROM golang:1.16-alpine

WORKDIR /usr/src/app

COPY . .

ENV PORT=8080

RUN go build

EXPOSE 8080

CMD ["./server"]