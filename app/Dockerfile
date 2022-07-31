FROM golang:1.19-rc-alpine

WORKDIR /app

COPY . ./

EXPOSE 3000

RUN go mod init goly
RUN go mod tidy

CMD ["go", "run", "main.go"]