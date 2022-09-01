FROM centos:7

FROM python:3.8-slim-buster

WORKDIR /code

MAINTAINER Devopscube

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY ssrf.py ssrf.py



COPY ss.sh ss.sh






ENTRYPOINT ["./ss.sh"]

EXPOSE 8080

