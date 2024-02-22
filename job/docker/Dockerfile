FROM ubuntu:20.04

USER root

ENV CYRIL_DEVELOP "192.168.71.108:8080"

ADD job /usr/bin/

COPY job.sh /

RUN chmod 777 /job.sh

CMD ["/job.sh"]
