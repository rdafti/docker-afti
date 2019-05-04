FROM ubuntu:latest

RUN apt update
RUN apt install -y python python-requests python-flask

COPY api.py /srv

WORKDIR /srv

CMD ["/usr/bin/python","/srv/api.py"]
