FROM alpine

RUN apk add --update rsyslog

COPY rsyslog.conf /etc/

VOLUME /var/run/rsyslog/dev

EXPOSE 514/tcp 514/udp

CMD ["rsyslogd", "-n"]
