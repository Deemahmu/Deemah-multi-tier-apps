FROM golang:1.22-alpine as builder

WORKDIR /app

COPY go.mod go.sum ./

RUN go mod download

COPY . . 

RUN go build -o main .

FROM scratch

COPY --from=builder /app/main /app/main

WORKDIR /app

EXPOSE 8080

USER 1000:1000

CMD ["./main"]
