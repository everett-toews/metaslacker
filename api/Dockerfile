FROM python:3.4

ENV PYTHONUNBUFFERED 1

ADD . /src

WORKDIR /src

RUN pip install -r requirements.txt

CMD gunicorn api:api -b 0.0.0.0:8000
