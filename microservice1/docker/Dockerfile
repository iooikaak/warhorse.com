FROM ubuntu:20.04

USER root

ENV CYRIL_DEVELOP "192.168.71.108:8080"

ADD microService1 /usr/bin/

COPY microService1.sh /

RUN chmod 777 /microService1.sh

CMD ["/microService1.sh"]
