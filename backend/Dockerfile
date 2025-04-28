FROM python:3.9.5-slim-buster

ADD . ./app

WORKDIR /app

RUN pip3 install -r backend/requirements.txt

EXPOSE 5003

CMD [ "python","app.py" ]
