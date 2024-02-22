FROM ubuntu:20.04

USER root

ENV CYRIL_DEVELOP "192.168.71.108:8080"

ADD microService2 /usr/bin/

COPY microService2.sh /

RUN chmod 777 /microService2.sh

CMD ["/microService2.sh"]
