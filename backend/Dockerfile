FROM alpine:3.19

RUN apk update && apk add --no-cache g++

WORKDIR /app

COPY app.cpp .

RUN g++ app.cpp -o app

EXPOSE 8080

CMD ["./app"]
