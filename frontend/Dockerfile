FROM python:3.9.5-slim-buster

ADD . ./app

WORKDIR /app

RUN pip3 install -r frontend/requirements.txt

EXPOSE 5004

CMD [ "python","app.py" ]
