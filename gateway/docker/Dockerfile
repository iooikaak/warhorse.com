FROM ubuntu:20.04

USER root

ENV CYRIL_DEVELOP "192.168.71.108:8080"

ADD gateway /usr/bin/

COPY gateway.sh /

RUN chmod 777 /gateway.sh

CMD ["/gateway.sh"]
