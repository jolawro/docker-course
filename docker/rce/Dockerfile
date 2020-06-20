FROM alpine

RUN apk add --update --no-cache curl py-pip

CMD ["8.8.8.8"]

ENTRYPOINT [ "ping", "-t", "5" ]