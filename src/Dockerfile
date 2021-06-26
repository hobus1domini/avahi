# Failing with newer version
FROM alpine:3.10

WORKDIR /opt

RUN apk add --no-cache avahi augeas

COPY entrypoint.sh ./entrypoint.sh

RUN chmod +x ./entrypoint.sh

ENTRYPOINT ["./entrypoint.sh"]
