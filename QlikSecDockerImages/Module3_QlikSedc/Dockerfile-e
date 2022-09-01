FROM python:3.8
WORKDIR /code

COPY clickjack.py clickjack.py
#COPY requirements.txt requirements.txt
RUN pip3 install urllib3
ENTRYPOINT [ "python3", "./clickjack.py" ]

EXPOSE 8080
