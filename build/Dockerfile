# Docker-tftpd

FROM python:3.11.4

RUN pip install flask && mkdir /opt/kek_code


COPY ./ /opt/kek_code

ENTRYPOINT ["/usr/local/bin/python3"]

CMD ["-m", "http.server", "8078"]

