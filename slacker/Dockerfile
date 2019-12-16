FROM alpine:latest
RUN apk add --no-cache ca-certificates

ADD slacker slacker
RUN chmod +x slacker

CMD ["./slacker"]

